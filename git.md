>Что такое метод в JS

Метод это блок кода которая работает каждый раз когда мы его завём.
# String  в JS
В JS мы можем писать стринг по три вида `Double Quotes` `Single Quotes` и `Backticks` 

* > Double Quotes
```js
console.log("Hello world")
```
* > Single Quotes
```js
console.log('Hello world')
```
* > Backticks
```js
let i = "world"
console.log(`Hello ${i}`)
```

## Методы  `String` в JS
1. charAt()
2. At()
3. concat()
4. trime()
5. includes()
6. indexOf()
7. replacce() ,replaceAll()
8. repeat()
9. slice()
10. substring()
11. split()
12. toString
13. toLowerCase
14. toUpperCase
15. ______________
    
## charAt()
Метод charAt() в JavaScript используется для получения символа на определенной позиции в строке. Он принимает индекс символа в качестве аргумента и возвращает символ по этому индексу.
```js
let text = "Hello"
console.log(text.charAt(2));
```

## аt()
Этот метод позволяет получать символы из строки, аналогично методу charAt(), но более удобно, чем использование квадратных скобок.
```js
let text = "Hello"
console.log(text.аt(2));
console.log(text.аt(-1));
```

## concat()
Метод concat() в JavaScript используется для объединения двух или более строк в одну новую строку. Он не изменяет исходные строки, а возвращает новую строку, содержащую комбинацию всех переданных ему строк.
```js
let str1 = "Hello";
let str2 = "beautiful";
let str3 = "world!";
let result = str1.concat(", ", str2, " ", str3);
console.log(result); // Выводит "Hello, beautiful world!"
```


## trime()
В JavaScript метод trim() используется для удаления начальных и конечных пробелов из строки. Пробельные символы в данном контексте включают в себя пробелы, табуляции, символы новой строки и другие "невидимые" символы, которые могут появляться при копировании текста.
```js
let str = "   Hello, world!   ";
let trimmedStr = str.trim();
console.log(trimmedStr); // Выводит "Hello, world!"
```


## includes()
Метод includes() в JavaScript используется для определения, содержит ли строка определенную подстроку. Он возвращает логическое значение true, если подстрока найдена в строке, и false в противном случае.<br>
Метод includes() также может принимать второй аргумент, который указывает на позицию, с которой начинать поиск подстроки:
```js
let str = "Hello, world!";
let substring = "world";
let isIncluded = str.includes(substring);
console.log(isIncluded); // Выводит true
```


## includes()
Метод includes() в JavaScript используется для определения, содержит ли строка определенную подстроку. Он возвращает логическое значение true, если подстрока найдена в строке, и false в противном случае.<br>
Метод includes() также может принимать второй аргумент, который указывает на позицию, с которой начинать поиск подстроки:
```js
let str = "Hello, world!";
let substring = "world";
let isIncluded = str.includes(substring);
console.log(isIncluded); // Выводит true
```

## indexOf()
Метод indexOf() в JavaScript используется для поиска первого вхождения подстроки в строке. Он возвращает индекс первого вхождения подстроки в строке или -1, если подстрока не найдена.
```js
let str = "Hello, world!";
let substring = "world";
let index = str.indexOf(substring);
console.log(index); // Выводит 7
```


## replacce() ,replaceAll()
В JavaScript методы replace() и replaceAll() используются для замены подстрок в строке на новую подстроку. Они предоставляют разные возможности и синтаксис.
```js
let str = "Hello, world!";
let newStr = str.replace("world", "universe");
console.log(newStr); // Выводит "Hello, universe!"
```
```js
let str = "Hello, world!";
let newStr = str.replaceAll("o", "0");
console.log(newStr); // Выводит "Hell0, w0rld!"
```


## repeat()
Метод repeat() в JavaScript используется для создания новой строки, которая содержит указанное количество копий исходной строки.
```js
let str = "Hello";
let repeatedStr = str.repeat(3);
console.log(repeatedStr); // Выводит "HelloHelloHello"
```


## slice()
Метод slice() в JavaScript используется для извлечения части строки и создания новой строки на основе этой части. Он принимает два аргумента: начальный и конечный индексы. Возвращаемая строка будет содержать символы с индекса, указанного в первом аргументе (включительно), до индекса, указанного во втором аргументе (не включая его).
```js
let str = "Hello, world!";
let slicedStr = str.slice(7, 12);
console.log(slicedStr); // Выводит "world"
```


## substring()
Метод substring() в JavaScript используется для извлечения части строки и создания новой строки на основе этой части. Он принимает два аргумента: начальный и конечный индексы. Возвращаемая строка будет содержать символы с индекса, указанного в первом аргументе (включительно), до индекса, указанного во втором аргументе (исключая его).
```js
let str = "Hello, world!";
let subStr = str.substring(7, 12);
console.log(subStr); // Выводит "world"
```



## split()
Метод split() в JavaScript используется для разделения строки на массив подстрок на основе указанного разделителя. Разделитель может быть строкой или регулярным выражением, которое определяет, где производить разделение.
```js
let str = "apple,banana,orange";
let fruits = str.split(",");
console.log(fruits); // Выводит массив ["apple", "banana", "orange"]
```

## toString
В JavaScript метод toString() используется для преобразования объекта в строковое представление. Этот метод доступен для большинства типов данных, включая числа, массивы, объекты, функции и т. д.
```js
let num = 123;
let str = num.toString();
console.log(str); // Выводит "123"
```
```js
let arr = [1, 2, 3];
let str = arr.toString();
console.log(str); // Выводит "1,2,3"
```


## toLowerCase
Метод toLowerCase() в JavaScript используется для преобразования всех символов строки в нижний регистр. Это полезно, когда вам нужно сравнивать строки без учета регистра символов или когда требуется привести строку к нижнему регистру для единообразного форматирования.
```js
let str = "Hello, WORLD!";
let lowerCaseStr = str.toLowerCase();
console.log(lowerCaseStr); // Выводит "hello, world!"
```


## toLowerCase
Метод toLowerCase() в JavaScript используется для преобразования всех символов строки в нижний регистр. Это полезно, когда вам нужно сравнивать строки без учета регистра символов или когда требуется привести строку к нижнему регистру для единообразного форматирования.
```js
let str = "Hello, WORLD!";
let lowerCaseStr = str.toLowerCase();
console.log(lowerCaseStr); // Выводит "hello, world!"
```


## toUpperCase
Метод toUpperCase() в JavaScript используется для преобразования всех символов строки в верхний регистр. Это полезно, когда вам нужно сравнивать строки без учета регистра символов или когда требуется привести строку к верхнему регистру для единообразного форматирования.
```js
let str = "Hello, world!";
let upperCaseStr = str.toUpperCase();
console.log(upperCaseStr); // Выводит "HELLO, WORLD!"
```


# Number
* Math.floor()
* Math.randum()
* Math.ceil()
* Math.max()
* Math.min()
* Math.NaN()
  