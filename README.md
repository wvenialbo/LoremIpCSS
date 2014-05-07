LoremIpCSS
==========
Version 1.0

CSS3 stylesheet with 150 paragraphs of Lorem Ipsum dummy text to be used with web page templates.


### Access to 150 paragraphs of Lorem ipsum dummy text.


Taken from the "lipsum" LaTeX package version 1.0 by Patrick Happel. All the paragraphs were (originally) taken with permission from http://lipsum.com/. With further thanks to James Wilson for that work.

This source file may be distributed and/or modified under the conditions of the Creative Commons Attribution 3.0 or (at your option) any later version, which means that you are free to download and use it for anything you want, including amending it.

Please send error reports and suggestions for improvements to Waldemar Villamayor-Venialbo <wvenialbo@gmail.com>.

Project repository: https://github.com/wvenialbo/LoremIpCSS


CSS selectors
-------------

The included style sheet ([lipsum.css](https://github.com/wvenialbo/LoremIpCSS/blob/master/lipsum.css)) defines CSS selectors for the following HTML classes:

* Header texts (phrases and sentences taken from the first 10 paragraphs of Lorem Ipsum)
  * `.lipsum-hdr-[#1] ` : for short headers
  * `.lipsum-lhdr-[#1]` : for long headers
* Complete sentence texts (all 18 sentences from the first paragraph of Lorem Ipsum)
  * `.lipsum-i-[#2]   ` : for short blocks of texts
* Full paragraph texts (150 paragraphs of Lorem ipsum)
  * `.lipsum-[#3]     ` : for paragraphs text samples

`[#1]` = roman numerals (`i` to `x`). See [lipsum.css](https://github.com/wvenialbo/LoremIpCSS/blob/master/lipsum.css) for details.

`[#2]` = roman numerals (`i` to `xviii`). See [lipsum.css](https://github.com/wvenialbo/LoremIpCSS/blob/master/lipsum.css) for details.

`[#3]` = roman numerals (`i` to `cl`). See [lipsum.css](https://github.com/wvenialbo/LoremIpCSS/blob/master/lipsum.css) for details.

Examples
--------

`<h1 class=".lipsum-hdr-i"></h1> ` ... renders to ... `<h1>Lorem Ipsum</p>`

`<h3 class=".lipsum-lhdr-i"></h3>` ... renders to ... `<h3>Lorem ipsum dolor sit amet</h3>`

`<em class=".lipsum-i-xv"></em>  ` ... renders to ... `<em>Curabitur auctor semper nulla.</em>`

`<p class=".lipsum-i"></p>       ` ... renders to ... `<p>Lorem ipsum ... dignissim rutrum.</p>`

*Note that complete sentences and paragraphs include the final period.*

Copyright (C) 2014, Waldemar Villamayor-Venialbo.