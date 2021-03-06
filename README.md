# DEIM-and-Thesis
DEIM2019予稿集用論文と卒業研究論文（以下，卒論）を執筆するためのテンプレート集です。
本テンプレートを利用することで，DEIM2019予稿集用論文をほぼ自動的に卒論に変換することができます。

執筆環境はLaTeXを想定しています。
Microsoft Wordで執筆したい学生は，別途テンプレートをダウンロードしてください。
DEIM2019予稿集用論文のテンプレート（.docx）は[こちら](http://db-event.jpn.org/deim2019/data/format_docx_deim2019_j.docx)から入手できます。

なお，静岡大学情報学部にはLaTeX版およびWord版卒論テンプレートは存在しません。
本レポジトリで用意している卒論用LaTeXテンプレートはあくまで山本個人が用意したものです。


## テンプレートの使い方
### for DEIM2019の予稿集用論文
1. 本レポジトリをダウンロードしてください。gitが使える人はforkしても構いません。
2. DEIMディレクトリのpaper.texの26行目にある\jtitle{論文のタイトル}を修正し，論文のタイトルを設定してください。
3. 同じくpaper.texの28行目にある\authorentry[hanako@design.inf.shizuoka.ac.jp]{静岡 花子}{Hanako Shizuoka}を修正し，著者情報として自分の名前，メールアドレスを設定してください。
4. contents/textディレクトリに論文の各章に対応するLaTeXファイルが置いてあります。各ファイルに論文コンテンツを書き込んでいってください。
5. （必要であれば）画像ファイルをcontents/figureディレクトリに配置してください。
6. 必要に応じてcontents/textディレクトリにあるdeim-acknowledgment.texを修正し，謝辞を記してください。
7. DEIMディレクトリに移動して，paper.texファイルをコンパイルしてください。同じディレクトリにPDFファイルが作成されます。

### for 卒論
上の方法でDEIM2019の予稿集用論文を作成している場合は簡単です。
下記手順に従って論文PDFを作成してください。

1. DEIM2019で書き足りなかった事項や修正したい事項があれば，contents/textディレクトリの各ファイルを修正・追記してください。
2. Thesisディレクトリのpaper.texの35行目にあるtitle{論文タイトル}を修正し，論文のタイトルを設定してください。
3. 同じくpaper.texの39行目の所属プログラム名，40行目の学籍番号，42行目の氏名を適宜修正してください。
4. 同じくpaper.texの27行目の副査について，担当副査の教員名を入力してください。
5. 必要に応じてcontents/textディレクトリにあるthesis-acknowledgment.texを修正し，謝辞を記してください。
6. Thesisディレクトリに移動して，paper.texファイルをコンパイルしてください。同じディレクトリにPDFファイルが作成されます。


## 論文の書き方
[学術分野における作文方法について](https://github.com/ymmt3-lab/lab-management/blob/master/how-to-write-a-paper.md)，解説記事を用意しています。これを読んでください。


## LaTeXの使い方について
Thesisディレクトリのpaper.pdfをご覧ください。


## 卒論スケジュール
* 2018年12月25日　**DEIM2019タイトル，アブストラクト**登録〆切
* 2019年1月10日　**DEIM2019予稿集用論文**の投稿〆切
* 2019年1月31日　**卒論審査用論文**の提出〆切
* 2019年2月7日　**卒論審査会**
* 2019年2月12日　DEIM2019参加登録締め切り，論文の修正〆切
* 2019年2月14日　卒論最終稿提出
* 2019年3年4日-6日　DEIM2019
* 2019年3月4日　臨時教授会 for 卒業判定
* 2019年3月20日　学位記授与式
