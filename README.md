# Eloquent JavaScript

These are the sources used to build the third edition of Eloquent
JavaScript (https://eloquentjavascript.net).

Feedback welcome, in the form of issues and pull requests.

## Building

This builds the HTML output in `html/`, where `make` is GNU make:

    npm install
    make html

To build the PDF file (don't bother trying this unless you really need
it, since this list has probably bitrotted again and getting all this
set up is a pain):

    apt-get install texlive texlive-xetex fonts-inconsolata fonts-symbola texlive-lang-chinese inkscape
    make book.pdf

## Translating

Translations are very much welcome. The license this book is published
under allows non-commercial derivations, which includes open
translations. If you do one, let me know, and I'll add a link to the
website.

A note of caution though: This text consists of about 130 000 words,
the paper book is 400 pages. That's a lot of text, which will take a
lot of time to translate.

If that doesn't scare you off, the recommended way to go about a
translation is:

 - Fork this repository on GitHub.

 - Create an issue on the repository describing your plan to translate.

 - Translate the `.md` files in your fork. These are
   [CommonMark](https://commonmark.org/) formatted, with a few
   extensions. You may consider omitting the index terms (indicated
   with double parentheses and `{{index ...}}` syntax) from your
   translation, since that's mostly relevant for print output.

 - Publish somewhere online or ask me to host the result.

Doing this in public, and creating an issue that links to your work,
helps avoid wasted effort, where multiple people start a translation
to the same language (and possibly never finish it). (Since
translations have to retain the license, it is okay to pick up someone
else's translation and continue it, even when they have vanished from
the internet.)

## Words list

This table is for special words that don't have kurdish meaning or i don't know them yet!
so please use this table as a guide for your translating too. (however if you know the kurdish word for it, please first make a pull request to this readme file and then if the maintainers agreed with you, the words will be replaced)

| English      | Kurdish |
| ----------- | ----------- |
| web | وێب|
| Website | ماڵپەڕ|
| interface | ڕووکار|
| tools | ئامراز|
| server | سێرڤەر|
| Versions | وەشانەکان|
| Modules | مۆدیولەکان|
| node | نۆد|
| Background | باکگراوند |
| Protocol | پرۆتۆکۆڵ|
| Browsers | وێبگەڕەکان|
| Radio | ڕادیۆ|
| buttons | دوگمەکان|
| Checkbox | چێک بۆکس|
| Data | داتا|
| keyboard |تەختەکلیل|
| Summary | کورتە|
| Exercises | ڕاهێنانەکان|
| application | ئەپڵیکەیشن|
| canva |کانڤا|
| component | پێکهاتەکان|
| Exercises | ڕاهێنانەکان|
| application | ئەپڵیکەیشن|
| state |دۆخ|
| Functions |فەنکشنکان|
| JavaScript | جاڤاسکڕێپت|
| Eloquent JavaScript | جاڤاسکریپتی ڕوون|
| Node.js | Node.js|
| DOM | DOM|
| HTML | HTML|
| HTTP | HTTP|
| HTTPS | HTTPS|
| NPM | NPM|
