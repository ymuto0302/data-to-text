# data-to-text
永田君の特別研究に関するコード

- <a href="seq2seq_with_attention.ipynb">seq2seq_with_attention.ipynb</a><br>
  seq2seq with attention : フランス語から英語への翻訳 (PyTorch の tutorial)<br>
  tutorial の丸パクリ (^^)
- <a href="e2e_data_handling.ipynb">e2e_data_handling.ipynb</a><br>
  E2E dataset の取り出し手順の確認 ＆ データの諸元を観察するコード
- <a href="seq2seq_with_attention_for_E2E.ipynb">seq2seq_with_attention_for_E2E.ipynb</a><br>
  seq2seq_with_attention.ipynb を E2E dataset 用に書き換えたコード<br>
  単純な seq2seq であり，[Dusk and Jurcicek, 2016] のように beam search / reranker を組み込んでいない。
- <a href="BLEU_example.ipynb">BLEU_example.ipynb</a><br>
  nltk.translate.bleu_score の使用例<br>
