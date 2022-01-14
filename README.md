# dot2pdf
 A script to convert DOT to PDF


## Overview

 `dot2pdf` is a script to convert DOT to PDF.
 `dot2tex`, `pdflatex`, and `pdfcrop` are used internally.


## Requirement

 - bash (> 3.2.57)
 - [dot2tex](https://dot2tex.readthedocs.io/en/latest/index.html) (> 2.11.3)
 - [TeX Live](https://www.tug.org/texlive/) (> 2011)
    - pdflatex
    - pdfcrop


## Usage
 To convert <tt><i>filename</i>.dot</tt> to <tt><i>filename</i>.pdf</tt>, all you just need to run the following command.

 <pre> $ dot2pdf <i>filename</i>.dot </pre>

 If you want to change the output path, you may run the following command.

 <pre> $ dot2pdf <i>filename</i>.dot <i>path_to_output</i>.pdf </pre>


<!--
## Features

## Reference
-->

## Author
 [yoshphys](https://github.com/yoshphys)

## Licence
 dot2pdf is under MIT license. See the [LICENSE](https://github.com/yoshphys/dot2pdf/blob/main/LICENSE) for more info.
