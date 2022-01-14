<!---
# Marks the first heading Level 1
...
down to 
....
###### level 6

Blank lines create paragraphs

**bold** will give you bold text

*italics* will give you a single italic

***bold and italic*** will give you bold and italic

> will give you blockquote

Just add > and > for each line for multi line block quote


To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period.

Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com> 
-->
# Python Tutorials by Zibusiso Masuku

## What is this file?
 All things to learn Python, biased for DS. Hopefully, I will be adding more directions in future.

## What I learnt? **The CHEAT Sheet**

## *The `print` Function*
The `print()` Allows Python to display output. So in case we want to print the iconic letters, we would say:  
`print("Hello World!")`

## *Arithemtic Operators*
- `+`	Addition
- `-`   Subtraction
- `*`	Multiplication
- `/`	Division
- `%`   Modulo operator, it returns to you the remainder in a Division process
- `**`	Exponentiation. For instance `2**3` can be read as `2` raised to the power of `3`.
- `//`	Integer division - quotient. For instance, `30//7` will return `4`, which is the integer value of the value `4.2857`
-  `^`	Bitwise XOR (usually outside scope)

=	#assignment operator

x, y, z = 2, 3, 5 #carries out sequential assignment, i.e., x=2, y =3, z=5

snake_case #Python's Preferred Naming Convention

+=	#Python's way of assigning a variable with itself

e.g., x += 2 same as x = x + 2, or x -= 2 same as x = x - 2, x *= 0.9 same as x = 0.9*x

type()	#checks type of object

#Data Types
int	#integer. whole numbers
float	#floats, all decimals and fractions
		##it's important to note that fractions are stored as approximations in Python (base 2 limitations)
bool #Boolean logic, data types with true or false
string


#Comparison Operators
<	#Less than
>	#Greater than
<=	#Less than or equal to
>=	#Greater than or equal to
==	#is equal to, checks if two variables are equal
!=	#is not equal to, checks if two variables are NOT equal

Logical Operators
and #checks boolean values of two statements, TRUE and TRUE shows TRUE, TRUE and FALSE shows FALSE, FALSE and FALSE sho
or
not

\ backslash allows python to skip quotation marks

#Mathematical Operations on Strings
+
*
len()