# boldfont
a latex package that bolds the first syllable of every word

## Explanation:
The *boldfont* package utilizes an existing string manipulation LaTeX package, *xstring*, to bold the first few characters of every string in a compiled LaTeX document.

The package works as follows:

1. Any string with <=2 characters will remain un-bolded.
2. Strings containing 3-4 characters will have the first two characters bolded.
3. Strings containing >4 characters will have the first three characters bolded.  
