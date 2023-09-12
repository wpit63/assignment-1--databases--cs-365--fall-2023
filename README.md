# Fall 2023 Principles of Databases — Assignment 1

* **Do not start this project until you have read these instructions carefully.**
* **Read these instructions repeatedly until you understand, then begin your project. If something is not clear, ask.**

## ❖・Introduction・❖

In this assignment, you’ll work in two languages: XML and JSON; one will mirror the other. For the XML part, you’ll create an XML document that represents students at a university, and you’ll author a grammar, via a DTD document, that will define the language of your XML document.

You’ll then convert the XML to its JSON equivalent.

---

## ❖・Details・❖

Your student is comprised of the following information:

* First name
* Middle name
* Last name
* Preferred name
* Student ID
* Email
* Phone
* Status (first year, second year, etc)
* GPA
* Major
* Minor
* Status (full-time, part-time, graduated, withdrawn)
* Advisor
* Date of initial enrollment
* Graduation date

---

## ❖・Rules・❖

### General

* Indent uniformly using 2, 3, or 4 spaces.
* Don’t mix tabs and spaces.
* Populate the XML and JSON documents with two distinct people who have the same first and last names.
* Implement the JSON and XML independently, then compare, as one will likely be more logical than the other.

### XML Section

* All your XML goes in `xml/index.xml`.
* All your CSS goes in `xml/css/style.css`.
* Your DTD goes in `xml/dtd/student.dtd`.
* Comment every line of your DTD.
* Author the DTD on your own; no help from WebStorm.
* Style your XML using CSS so it’s easy to read in the browser.
* Expose any XML attribute to the front end using CSS’s [`content`](https://developer.mozilla.org/en-US/docs/Web/CSS/content) property and [`attr()`](https://developer.mozilla.org/en-US/docs/Web/CSS/attr) function.

### JSON

* Validate your JSON directly in your editor and/or at [jslint.com](http://jslint.com/).

## ❖・Due・❖

Wednesday, 20 September 2023, at 10:00 PM.

## ❖・Grading・❖

| Item                     | Points |
|--------------------------|:------:|
| *XML Implementation*     | `20`   |
| *DTD Implementation*     | `20`   |
| *JSON Implementation*    | `20`   |
| *Code Quality*           | `20`   |
| *Following Instructions* | `20`   |

**NO late submissions will be accepted.**

## ❖・Submission・❖

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may *only* be submitted via GitHub. **No other form of submission will be accepted**.
