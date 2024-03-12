# Software Requirements Specifications Documentation in LaTeX
Made for Software and Knowledge Engineering students who enrolled in Project Preparation course. The document is written in LaTeX and requires at least LaTeX2e to parse the template.

## Prerequisites
It is recommended to use Visual Studio Code to open the `main.code-workspace` file, and it is recommended to install the `LaTeX Workshop` extension (you can get it from the Extensions Store).
* TeX Distribution w/ LaTeX
  * You can use MikTeX as the distribution that will manage installations of LaTeX packages for you, however you will also need to install `perl`.

## Instructions
* To start using the template, clone the repository or fork into your own repository.
* You should be editing the `document.tex` first, but only the part where there are variables for your project.
  ```tex
  %% -----------------------------------
  % Edit the variables for the paper here!
  \def \srsTitle{Project Title}
  \def \srsAuthorOne{Name Surname}
  \def \srsAuthorTwo{Name Surname}
  \def \srsAuthorThree{Name Surname}
  \def \srsAcademicYear{YYYY}

  \def \srsAdvisorName{Project Advisor's Name}
  \def \srsCoAdvisorName{Project Co-Advisor's Name}
  \def \srsHoDName{Head of Department's Name}
  %% -----------------------------------
  ```
  You may edit the values in the `{ }`.
* After that, you can start on editing the files in `body` directory. However, do note that extra packages to be used must be defined within the premable of `document.tex`.
* If you are using Visual Studio Code with the pre-included workspace, you can hit run and a PDF file will be generated which you can find it in `out` directory.

## Extra Packages - for use cases
* `pgfplots` - a plotting and graphing package for LaTeX.
* `xskak` - a chess notation + chessboard package for illustrating chess game in LaTeX.
* `minted` - code syntax highlighting in LaTeX document.
More packages can be found in the Comprehensive TeX Archive Network (CTAN) Website.