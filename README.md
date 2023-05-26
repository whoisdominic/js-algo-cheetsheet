# Interview CheatSheet

Iterate in reverse
```javascript 
for (let i = array.length; i >= 0; i--)
```
#### Set

| Method     | Description                                                                |
|------------|----------------------------------------------------------------------------|
| new Set()  | Creates a new Set                                                          |
| add()      | Adds a new element to the Set                                               |
| delete()   | Removes an element from a Set                                               |
| has()      | Returns true if a value exists                                             |
| clear()    | Removes all elements from a Set                                            |
| forEach()  | Invokes a callback for each element                                        |
| values()   | Returns an Iterator with all the values in a Set                            |
| keys()     | Same as values()                                                           |
| entries()  | Returns an Iterator with the [value,value] pairs from a Set                 |

And here is the property table:

| Property   | Description                                   |
|------------|-----------------------------------------------|
| size       | Returns the number elements in a Set          |

#### Map

| Method     | Description                                                                |
|------------|----------------------------------------------------------------------------|
| new Map()  | Creates a new Map object                                                    |
| set()      | Sets the value for a key in a Map                                           |
| get()      | Gets the value for a key in a Map                                           |
| clear()    | Removes all the elements from a Map                                         |
| delete()   | Removes a Map element specified by a key                                    |
| has()      | Returns true if a key exists in a Map                                       |
| forEach()  | Invokes a callback for each key/value pair in a Map                         |
| entries()  | Returns an iterator object with the [key, value] pairs in a Map             |
| keys()     | Returns an iterator object with the keys in a Map                           |
| values()   | Returns an iterator object of the values in a Map      

#### Arrays

| Method         | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| push()         | Adds one or more elements to the end of an array and returns the new length of the array. |
| pop()          | Removes the last element from an array and returns that element.                           |
| shift()        | Removes the first element from an array and returns that element.                          |
| unshift()      | Adds one or more elements to the front of an array and returns the new length of the array. |
| slice()        | Returns a shallow copy of a portion of an array into a new array object.                  |
| splice()       | Changes the contents of an array by removing or replacing existing elements and/or adding new elements in place. |
| join()         | Joins all elements of an array into a string.                                             |
| reverse()      | Reverses the order of the elements in an array.                                           |
| concat()       | Merges two or more arrays.                                                                |
| forEach()      | Executes a provided function once for each array element.                                 |
| map()          | Creates a new array populated with the results of calling a provided function on every element in the calling array. |
| filter()       | Creates a new array with all elements that pass the test implemented by the provided function. |
| reduce()       | Applies a function against an accumulator and each element in the array (from left to right) to reduce it to a single output value. |
| some()         | Tests whether at least one element in the array passes the test implemented by the provided function. |
| every()        | Tests whether all elements in the array pass the test implemented by the provided function. |
| find()         | Returns the value of the first element in the array that satisfies the provided testing function. Otherwise undefined is returned. |
| indexOf()      | Returns the first index at which a given element can be found in the array, or -1 if it is not present. |
| findIndex()    | Returns the index of the first element in the array that satisfies the provided testing function. Otherwise, it returns -1. |
| includes()     | Determines whether an array includes a certain value among its entries.                    |
| sort()         | Sorts the elements of an array in place and returns the array.                             |
| flat()         | Creates a new array with all sub-array elements concatenated into it recursively up to the specified depth. |
| flatMap()      | Returns a new array formed by applying a given callback function to each element of the array, and then flattening the result by one level. |
| fill()         | Changes all elements in an array to a static value, from a start index (default 0) to an end index (default array.length). |                     |

#### Strings

| Method         | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| charAt()       | Returns the character at the specified index.                                          |
| concat()       | Combines the text of two strings and returns a new string.                             |
| includes()     | Determines whether one string may be found within another string.                      |
| indexOf()      | Returns the index within the calling String object of the first occurrence of the specified value. |
| lastIndexOf()  | Returns the index within the calling String object of the last occurrence of the specified value. |
| match()        | Used to match a regular expression against a string.                                   |
| replace()      | Used to replace a specified value with another value in a string.                      |
| search()       | Executes a search for a match between a regular expression and this String object.     |
| slice()        | Extracts a section of a string and returns it as a new string.                         |
| split()        | Splits a String object into an array of strings by separating the string into substrings. |
| substr()       | Returns the characters in a string beginning at the specified location through the specified number of characters. |
| substring()    | Returns the characters in a string between two indexes into the string.                |
| toLowerCase()  | Returns the calling string value converted to lowercase.                               |
| toUpperCase()  | Returns the calling string value converted to uppercase.                               |
| trim()         | Trims whitespace from the beginning and end of the string.                             |
| trimStart()    | Trims whitespace from the beginning of the string.                                     |
| trimEnd()      | Trims whitespace from the end of the string.                                          |
| startsWith()   | Determines whether a string begins with the characters of a specified string.          |
| endsWith()     | Determines whether a string ends with the characters of a specified string.            |
| repeat()       | Constructs and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together. |
| length         | Returns the length of the string.                                                      |
