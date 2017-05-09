# Processing

https://processing.org/

## 入手から起動まで

1. ダウンロード http://www.processing.org/
		* Download Processingを選ぶ
		* WindowsかWindows(without Java)を選ぶ。
2. 解凍する
		* Windowsの場合、解凍したフォルダは「C:」直下においたほうがいい。
		* 最初は平気だけど、ライブラリをインポートしたとき、エラーになる
3. 「Processing.exe」アイコンをダブルクリック
これで、Processingが起動します。

## とりあえず絵を描く

次のように入力して、ツールバーの「Run」ボタンをクリック。

line(0,0,200,200);
これで、左上から右下に直線(Line)が描きます。カッコ内は、（x1, y1, x2, y2）を順に指定してします。「x1, y1」が線の一方の端の座標。「x2, y2」が、もう一方の端の座標です。

しかし、なぜかWinの場合なにも表示出ない！！！

processing-pic1.png

次はこれ。

size(250, 250);
ellipse(120,120,80,80);
描画ウィンドウのサイズ(Size)を変更して、その円(ellipse:楕円)を描きます。

ellipse.png

Sizeのカッコ内は、横幅(width)と縦幅(height)の順に指定します。ellipseのカッコの中は、次の順に指定します。

ellipse(x, y, width, height);
x=中心の横の位置 y=中心の縦の位置 width=楕円の横幅 height=楕円の縦幅

ちなみにProcessingでは、行末に必ず「;」を入力します。コードが2行以上あると上から順番に実行していきます。

## 参考：

* http://mslabo.sakura.ne.jp/WordPress/make/index/ -- PROCESSINGで始めるゲーム作りとコンピュータ
