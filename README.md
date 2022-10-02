# Whyolet Font

Let's try to make a **simple** font:

* Latin alphabet has relatively few letters and is widely used.
* All languages can be transliterated to latin letters.
* There are 26 big and 26 small latin letters.
* Sometimes we are required to use big letters only: for clarity.
* Some alphabets like Georgian don't have a split to big and small letters.
* So let's use just 26 latin letters, selecting a simpler letter from big and small ones.
* And we need 10 arabic digits, also widely used.
* 26 + 10 = 36, so we can put the alphabet into a simple square table 6x6.
* We can use a simple square grid 3x3 to draw each letter and digit.
* Acctually all digits and most letters can use 2x3 grid.
* So let's avoid middle vertical line unless required.
* Let's use as few simple straight lines as possible to make it clear which symbol it is.
* If we do need big letters, then just add one more line near main vertical line.
* Each letter and digit should not lead to confusion like letter O and digit 0.
* The same form of a symbol can be reused multiple times using rotation.
* Symbols are grouped using consistent style, e.g. letters S and Z vs digits 5 and 2.
* Some words like russian "лишили" are handwritten as a series of connected spikes,  
  making it almost impossible to read it, unless letters are split.
* So letters should have space around, even handwritten.

TODO:
* Review.
* TTF font file.
* Try to use it for Whyolet website and products.
* On success, implement all [requirements](https://googlefonts.github.io/gf-guide/) to upload to [Google Fonts](https://fonts.google.com/).
