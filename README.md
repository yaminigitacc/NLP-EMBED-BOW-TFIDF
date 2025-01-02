# NLP-EMBED-BOW-TFIDF
NLP_ALGO_WORD_EMBEDDED_MODELS_BOW/TFIDF

Basically to build ML models on NLP text to be preprocessed and cleaned

As NLP tokens are text we should covert them into vectors with help of BOW and TFIDF.

BOW - which is CountVectorizer from sklearn library  
-- tokens will be vectorized as based their repetition in sentences.

--from sklearn.feature_extraction.text import CountVectorizer


TFIDF --- tfidfVectorizer from sklearn library

--to resolve the ambiguity from Count Vectorization we will build TFIDF to resolve generate decimal vectorized values.

-- from sklearn.feature_extraction.text import TfidfVectorizer
