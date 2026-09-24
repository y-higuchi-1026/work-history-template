# work-history-template

本リポジトリは、職務経歴書および PDF 変換を行うためのテンプレートです。

## 機能

- Markdown で作成する職務経歴書のテンプレートを用意
- VSCode 拡張機能を用いた、職務経歴書の PDF 変換
- 上記 PDF 変換における CSS を用いた簡易なスタイリング

## テンプレートの導入手順

1. GitHub 上で、本リポジトリの `Use this Template` -> `Create a new repository` をクリック
2. 任意のリポジトリ名を入力し、リポジトリを作成

## ローカルでの初回手順

1. 作成したリポジトリを clone する
2. VSCode 等で clone した本リポジトリのディレクトリを開く
3. 本リポジトリで推奨している下記3つの VSCode 拡張機能をインストールする (ディレクトリを開いた際にインストールの案内が出る)
   1. [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
   2. [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
   3. [Markdown Table](https://marketplace.visualstudio.com/items?itemName=TakumiI.markdowntable)
4. `template.md` が職務経歴書のテンプレートファイルであるため、これをコピーして職務経歴書を作成する

## PDF 変換手順

1. VSCode 上で変換対象の Markdown ファイルを開く
2. Markdown テキスト上で右クリックし、`Markdown PDF: Export (pdf)` を選択
3. 変換対象の Markdown ファイルと同名の PDF ファイルが出力される

## PDF のスタイリング

PDF 変換にあたって、`md-style.css` で簡易なスタイリングを適用しています。

必要があれば、このファイルでデザインの変更を行なってください。
