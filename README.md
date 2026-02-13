# 情報処理学会全国大会Latexテンプレート
本リポジトリはCloud Latex上で動作する情報処理学会全国大会のテンプレートです．

また，ローカル環境での動作は確認していません．

## 仕様
* A4 2段組み 
    * 上マージン30mm，下マージン 25mm，左マージン20mm，右マージン20mm，コラム間マージン7mm
* ページ番号なし


# 使用方法 

1. 右上のCodeをクリックして，ZIP形式で本リポジトリをダウンロード

<p align="center">
  <img src="https://github.com/user-attachments/assets/8d9e950e-6964-4b5d-92e0-786558e667b8" width="500">
</p>

2. [Cloude Latex](https://cloudlatex.io/ja)を開き，ページ下部にあるマイページをクリック
(Cloud Latexのアカウントがない場合は作成してください)

<p align="center">
  <img src="https://github.com/user-attachments/assets/528adca4-491d-459f-a413-b4ed64f7f16d" width="500">
</p>

3. 新規プロジェクトをクリック

<p align="center">
  <img src="https://github.com/user-attachments/assets/8dece3dc-4bf5-40a7-b50f-76cbca194568" width="500">
</p>

4. ダウンロードしたZIPファイルを選択して，uplatex形式でプロジェクトを作成

<p align="center">
  <img src="https://github.com/user-attachments/assets/b792274d-155a-4ff9-875f-570fbd58c4eb" width="500">
</p>

5. 好きなようにファイルを変更してコンパイルしてください．
また，PDFをクリックすることでPDFにできます．

<p align="center">
  <img src="https://github.com/user-attachments/assets/5551ff81-20f8-4f89-9404-8e37d2e8b667" width="500">
</p>

本リポジトリのままコンパイルすると警告が5つ表示されますが，問題なく原稿作成可能なため，警告は無視してOKです．

## 原稿作成に便利なサイト
Latexで原稿を作成する際に有益なサイトを紹介します．
* [表作成サイト](https://www.tablesgenerator.com/)
    * Latex形式の表を直感的に作成できます．

* 写真をeps形式に変更([jpg-eps](https://www.freeconvert.com/ja/jpg-to-eps), [png-eps](https://www.freeconvert.com/ja/png-to-eps))
    * eps形式にすることでPDFを拡大しても画像の滑らかさを保持します．

* [箇条書き](https://takataninote.com/tex/item.html)
    * 箇条書き方を様々な形式で紹介

## 謝辞
ipsj.styファイルで定義した，本ファイルの体裁は[yk-labさん](https://github.com/yk-lab/ipsj_national_convention_template/blob/master/ipsj.sty)のコードを一部使用しました．ありがとうございます．

## LICENSE
* 本プロジェクトは原則として MIT License の下で配布されています．
ただし、ipsj.sty に由来する一部のコードには BSD 2-Clause License が適用されます．
* This project is licensed under MIT License,
except for portions derived from ipsj.sty,
which are licensed under the BSD 2-Clause License.

* © 2026 yossyhira
