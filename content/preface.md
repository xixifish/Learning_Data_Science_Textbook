# Preface
 
Data science is exciting work. The ability to draw insights from messy data
is valuable for all kinds of decision making across business, medicine, policy, and
more. This book, _Learning Data Science_, aims to prepare readers to do data
science. To achieve this, we've designed this book with the following special features:

Focus on the fundamentals
: Technologies come and go. While we work with specific technologies in this book, our goal is to equip readers with the fundamental building blocks of data science. We do this by revealing how to think about data science problems and challenges, and by covering the fundamentals behind the individual technologies.  Our aim is to serve readers even as technologies change.

Cover the entire data science lifecycle
: Instead of just focusing on
   a single topic, like how to work with data tables or how to apply machine learning techniques, we cover
   the entire data science lifecycle—the process of asking a question,
   obtaining data, understanding the data, and understanding the world. This can often be the hardest part of being a data scientist.

Use real data
: To be prepared for working on real problems, we consider
   it essential to learn from examples that use real data, with their warts and all. We chose the datasets presented in this book by carefully picking from actual data analyses that have made an impact, rather than using overly refined or synthetic data.

Apply concepts through case studies
: We've included extended case
   studies throughout the book that follow or extend analyses from other
   data scientists. These case studies show readers how to navigate the data science lifecycle in real settings.

Combine both computational and inferential thinking
: On the job, data scientists
   need to foresee how the decisions they make when writing code and how the size of a 
   dataset might affect statistical analysis. To prepare readers for their future work,
   _Learning Data Science_ integrates computational and statistical thinking. We
   also motivate statistical concepts through simulation studies rather than
   mathematical proofs.

The text and code for this book are open source and [available on
GitHub][github].

[github]: https://github.com/DS-100/textbook/

## Expected Background Knowledge

We expect readers to be proficient in Python and understand how to use
built-in data structures like lists, dictionaries, and sets; import and use
functions and classes from other packages; and write functions from scratch. We
also use the `numpy` Python package without introduction but don't expect
readers to have much prior experience using it.

Readers will get more from this book if they also know a bit of probability,
calculus, and linear algebra, but we aim to explain mathematical ideas
intuitively.

## Organization of the Book

This book has 21 chapters, divided into six parts:

Part 1 (Ch 1-5)
: The Data Science Lifecycle describes what the
  lifecycle is, makes one full pass through the lifecycle at a basic level, and
  introduces terminology that we use throughout the book. The part concludes
  with a short case study about bus arrival times.

Part 2 (Ch 6-7)
: Rectangular Data introduces data frames and
  relations and how to write code to manipulate data using `pandas` and SQL.

Part 3 (Ch 8-12)
: Understanding the Data is all about obtaining data,
  discovering its traits, and spotting issues. After understanding these
  concepts, a reader can take a data file and describe the dataset's
  interesting features to someone else. This part ends with a case study
  about air quality.

Part 4 (Ch 13-14)
: Other Data Sources looks at widely used alternative sources of
  data like text, binary, and data from the web.

Part 5 (Ch 15-18)
: Linear Modeling focuses on understanding the world
  using data. It covers inferential topics like confidence intervals and
  hypothesis testing in addition to model fitting, feature engineering, and model selection.
  This part ends with a case study about predicting donkey weights for
  veterinarians in Kenya.

Part 6 (Ch 19-21)
: Classification completes our study of supervised
  learning with logistic regression and optimization. It ends with a case
  study on predicting whether news articles make real or fake statements.

At the end of the book, we included resources to learn more
about many of the topics this book introduces, and we provided the complete list of datasets used throughout the book.

## Conventions Used in This Book

The following typographical conventions are used in this book:

_Italic_
: Indicates new terms, URLs, email addresses, filenames, and file
extensions.

`Constant width`
: Used for program listings, as well as within paragraphs to
refer to program elements such as variable or function names, databases, data
types, environment variables, statements, and keywords.

**`Constant width bold`**
: Shows commands or other text that should be typed
literally by the user.

_`Constant width italic`_
: Shows text that should be replaced with
user-supplied values or by values determined by context.

```{note}
This element signifies a general note.
```

```{warning}
This element indicates a warning or caution.
```

## Using Code Examples

Supplemental material (code examples, exercises, etc.) is available for
download at _https://learningds.org_.

If you have a technical question or a problem using the code examples, please email to bookquestions@oreilly.com.

This book is here to help you get your job done. In general, if example code is
offered with this book, you may use it in your programs and documentation. You
do not need to contact us for permission unless you’re reproducing a
significant portion of the code. For example, writing a program that uses
several chunks of code from this book does not require permission. Selling or
distributing examples from O'Reilly books does require permission. Answering a
question by citing this book and quoting example code does not require
permission. Incorporating a significant amount of example code from this book
into your product's documentation does require permission.

We appreciate attribution. An attribution
usually includes the title, author, publisher, and ISBN. For example: "_Learning
Data Science_ by Sam Lau, Joseph Gonzalez, and Deborah Nolan (O'Reilly). Copyright
2023 Sam Lau, Joseph Gonzalez, and Deborah Nolan, 978-1-098-11300-1."

If you feel your use of code examples falls outside fair use or the permission
given above, feel free to contact us at bookquestions@oreilly.com.

## O'Reilly Online Learning

```{note}
For more than 40 years, [O'Reilly Media](https://oreilly.com)
has provided technology and business training, knowledge, and insight to
help companies succeed.
```

Our unique network of experts and innovators share their knowledge and
expertise through books, articles, and our online learning platform. O’Reilly’s
online learning platform gives you on-demand access to live training courses,
in-depth learning paths, interactive coding environments, and a vast collection
of text and video from O'Reilly and 200+ other publishers. For more
information, visit [https://oreilly.com](https://oreilly.com).

## How to Contact Us

Please address comments and questions concerning this book to the publisher:

<ul class="simplelist">
  <li>O’Reilly Media, Inc.</li>
  <li>1005 Gravenstein Highway North</li>
  <li>Sebastopol, CA 95472</li>
  <li>800-998-9938 (in the United States or Canada)</li>
  <li>707-829-0515 (international or local)</li>
  <li>707-829-0104 (fax)</li>
</ul>

Email bookquestions@oreilly.com to comment or ask technical questions about
this book.

For news and information about our books and courses, visit https://oreilly.com.

Find us on Facebook: https://facebook.com/oreilly

Follow us on Twitter: https://twitter.com/oreillymedia

Watch us on YouTube: https://www.youtube.com/oreillymedia

## Acknowledgments

This book has come about from our joint experience designing and teaching "Principles and Techniques of Data Science," an undergraduate
course at the University of California, Berkeley. We first taught "Data 100" in spring 2017 in response to student demand for a second course in data science; they wanted a course that would prepare them for advanced study in data science and for the workforce. 

The thousands of students we have taught since that first offering have been an inspiration for us. We've also benefited from co-teaching with other instructors, including Ani Adhikari, Andrew Bray, John DeNero, Sandrine Dudoit, Will Fithian, Joe Hellerstein, Josh Hug, Anthony Joseph, Scott Lee, Fernando Perez, Alvin Wan, Lisa Yan, and Bin Yu. We especially thank Joe Hellerstein for insights around data wrangling, Fernando Perez for encouraging us to include more complex data structures like NetCDF, Josh Hug for the idea of the PurpleAir case study, and Duncan Temple Lang for collaboration on an earlier version of the course. We also
thank the Berkeley students who have been our teaching assistants, and especially mention those who have contributed to previous versions of the
book: Ananth Agarwal, Ashley Chien, Andrew Do, Tiffany Jann, Sona Jeswani,
Andrew Kim, Jun Seo Park, Allen Shen, Katherine Yen, and Daniel Zhu.

A core part of this book are the many datasets that we wrangle and analyze, and we are immensely thankful to the individuals and organizations that made their data open and available to us. At the end of this book, we list these contributors along with the original data sources, and related research papers, blog posts, and reports. 

Lastly, we are grateful to the O'Reilly team for their work to bring this book from class notes to publication, especially Melissa Potter, Jess Haberman, Aaron Black, Danny
Elfanbaum, and Mike Loukides. We'd also like to thank the technical reviewers whose comments have improved the book: Sona Jeswani, Thomas Nield, Siddharth Yadav, and Abhijit Dasgupta.
