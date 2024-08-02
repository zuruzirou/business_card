a
# business_card

本リポジトリはマーカー・ベースを使用して、コンテンツを表示します。  
名刺を例にしていますが、内容は任意に変更可能です。自身の3Dモデルを表示すると面白いかもしれませんね。

# 自分用のAR名刺作成手順

ざっくり手順

1. 本リポジトリをFork
1. QRコードとマーカーファイル（patt）を再作成
1. コミット（Pages更新）

## 公開URLの作成

Forkするだけですが、一応表示を確認しておきましょう。
1. fork
1. Pagesの設定
    1. Settings -> Pages -> Branch指定してSave

ブラウザから表示を確認。カメラ使用を許可。  
https://study-demo-qst.github.io/business_card

QR.pngをカメラで表示すると、動画が再生されることを確認。

## QRコードの作成

本リポジトリのQRコードは、本リポジトリのPages URLから作成しています。  
これを自身のURLに置き換えて下さい。どこに公開しても良いですが、GitHub Pagesが簡単だと思います。  

[QR Code Generator](https://ja.qr-code-generator.com/)
1. 公開URL　※「公開URLの作成」参照
1. ダウンロードをクリック
1. しばらく待つ（ダイアログは無視して OK）

## マーカーファイルの作成

AR名刺を表示するQRコードか判定するために、マーカーファイルを作成します。  

作成方法は何でも良いですが、以下のサイトが簡単だと思います。  
https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html

UPLOAD -> DOWNLOAD MARKER  

作成したマーカーファイルをリポジトリの「marker.patt」と置き換えて下さい。

## 動作確認

修正をコミットし、リポジトリに反映。数分待つとPagesにも反映されるので、確認して下さい。

## おまけ

動作確認はChromeで行って下さい。Edgeでは表示できませんでした。
