# recommend_NMF
## 概要
・ユーザにおすすめの映画を5つ推薦するシステム。  
・行列因子分解手法NMFを使った、シンプルな協調フィルタリングを用いています。  
・言語は Python 2.7。  

## 使い方
python recommend.py  
で実行できます。  
実行すると user ID を要求され、  
整数で入力するとそのユーザへの推薦が行われます。  

## データセット  
下記のURLのMovieLens 100K Dataset を使用。  
http://grouplens.org/datasets/movielens/  
「ml-100k/」にそのまま入っています。  

ざっくりまとめると、以下のようなデータです。  
・各ユーザが映画につけた評価(1~5)とタイムスタンプ  
・映画の特徴量  
・ユーザの特徴量
