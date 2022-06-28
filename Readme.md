# CourseHero Document Generator

CourseHero Document Generator is a Python3 script to automatically generate documents. This project works by paraphrasing existing wikipedia articles and writing the paraphrased text to a word document that you can upload to coursehero. These documents can be used for various purposes including uploading to Coursehero.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install dependencies.

```bash
pip install -r requirements.txt
```

## Usage

Configure the wikipedia article you want to generate your documents on in the config.json file.

```python
python generate_documents.py <Number of documents you wants to generate>
```
