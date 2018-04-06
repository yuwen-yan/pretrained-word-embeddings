#
Pretrained Word Embeddings


## English Corpus

#### word2vec

Pre-trained vectors trained on part of Google News dataset (about 100 billion words). The model contains 300-dimensional vectors for 3 million words and phrases. The phrases were obtained using a simple data-driven approach described in [this paper](http://arxiv.org/pdf/1310.4546.pdf)

[download link](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing) | [source link](https://code.google.com/archive/p/word2vec/)

#### fastText

1 million word vectors trained on Wikipedia 2017, UMBC webbase corpus and statmt.org news dataset (16B tokens).

[download link](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki-news-300d-1M.vec.zip) | [source link](https://fasttext.cc/docs/en/english-vectors.html)

1 million word vectors trained with subword infomation on Wikipedia 2017, UMBC webbase corpus and statmt.org news dataset (16B tokens).

[download link](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki-news-300d-1M-subword.vec.zip) | [source link](https://fasttext.cc/docs/en/english-vectors.html)

2 million word vectors trained on Common Crawl (600B tokens).

[download link](https://s3-us-west-1.amazonaws.com/fasttext-vectors/crawl-300d-2M.vec.zip) | [source link](https://fasttext.cc/docs/en/english-vectors.html)

#### GloVe


Wikipedia 2014 + Gigaword 5 (6B tokens, 400K vocab, uncased, 50d, 100d, 200d, & 300d vectors, 822 MB download)

[download link](http://nlp.stanford.edu/data/glove.6B.zip) | [source link](https://nlp.stanford.edu/projects/glove/)

Common Crawl (42B tokens, 1.9M vocab, uncased, 300d vectors, 1.75 GB download)

[download link](http://nlp.stanford.edu/data/glove.42B.300d.zip) | [source link](https://nlp.stanford.edu/projects/glove/)

Common Crawl (840B tokens, 2.2M vocab, cased, 300d vectors, 2.03 GB download)

[download link](http://nlp.stanford.edu/data/glove.840B.300d.zip) | [source link](https://nlp.stanford.edu/projects/glove/)

Twitter (2B tweets, 27B tokens, 1.2M vocab, uncased, 25d, 50d, 100d, & 200d vectors, 1.42 GB download)

[download link](http://nlp.stanford.edu/data/glove.twitter.27B.zip) | [source link](https://nlp.stanford.edu/projects/glove/)

## Chinese Corpus

#### word2vec

Wikipedia database, Vector Size 300, Corpus Size 1G, Vocabulary Size 50101, Jieba tokenizor

[download link](https://drive.google.com/open?id=0B0ZXk88koS2KNER5UHNDY19pbzQ) | [source link](https://github.com/Kyubyong/wordvectors)

#### fastText

Trained on Common Crawl and Wikipedia using fastText. These models were trained using CBOW with position-weights, in dimension 300, with character n-grams of length 5, a window of size 5 and 10 negatives. We used the Stanford word segmenter for Tokenization

[download link](https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.zh.300.vec.gz) | [source link](https://fasttext.cc/docs/en/crawl-vectors.html)


## Reference

> https://github.com/Hironsan/awesome-embedding-models
> http://ahogrammer.com/2017/01/20/the-list-of-pretrained-word-embeddings/
> https://code.google.com/archive/p/word2vec/
> https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md
> https://fasttext.cc/docs/en/english-vectors.html
> https://arxiv.org/pdf/1310.4546.pdf
