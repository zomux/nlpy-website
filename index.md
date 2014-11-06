nlpy - A NLP tookit focusing on high level tasks 
===

(still in process)

### Installation
```bash
$ pip install nlpy
```
or
```bash
$ git clone https://github.com/zomux/nlpy.git
```

### Requirements
- nltk (for general pre-processing)
- gensim (for word2vec)
- numpy

### Semantic Searching

```python
>>> from nlpy.tasks import SemanticSearcher
>>> searcher = SemanticSearcher()
>>> searcher.load_data(["Dogs are good friends for human beings.", "New tennis court has been built in the school."])
>>> searcher.search("I want a pet.")
Dogs are good friends for human beings.
```


A list of other NLP softwares based on Python
===

