# LaTeX Project Files

This repository contains a collection of LaTeX files, including:

- my resume (CV) in English [[PDF]](https://github.com/xmsa/TexTemplate/blob/main/MY%20CV/resume.pdf)
- A report template
- The official University of Isfahan thesis template
- Required fonts for proper Persian rendering

---

## 📁 Directory Structure

```text
.
├── fonts/                         # Required Persian fonts
├── MY CV/
│   ├── resume.tex                 # Main LaTeX source for the resume
│   └── resume.pdf                 # Compiled resume
├── report-template/              # General academic/project report template
├── Thesis Isfahan template/
│   ├── Thesis.tex                # Main file to compile the full thesis
│   └── content_render.tex        # Partial content file (useful for focused editing)
└── README.md                     # This file
````

---

## 📘 University of Isfahan Thesis Template

Located in the `Thesis Isfahan template/` directory.

* **Main file**: `Thesis.tex`
  Compile this file to build the complete thesis document.

* **Partial content file**: `content_render.tex`
  Useful for editing/testing specific sections without compiling the entire thesis.

> ⚠️ Make sure the required fonts from the `fonts/` directory are installed before compiling.

---

## 📄 Resume

Located in the `MY CV/` directory.

* `resume.tex`: Source LaTeX file for your CV
* `resume.pdf`: Compiled version of your resume (ready to share)

This document is designed to support both Persian and English layout and typography.

---

## 🧰 Report Template

Found in the `report-template/` directory, this LaTeX template is suitable for:

* Course reports
* Technical documentation
* Research papers

Includes a standard layout, Persian language support, and well-formatted sections.

---

## 🛠 How to Compile

Use a LaTeX editor and compiler that supports Persian (like **XeLaTeX**). Recommended editors:

* **TeXstudio**
* **Overleaf**

### Example (from terminal):

```bash
cd "Thesis Isfahan template"
xelatex Thesis.tex
```
---

## 📬 Contact

Feel free to open an issue or contact me if you find a bug or have a suggestion for improvement.


