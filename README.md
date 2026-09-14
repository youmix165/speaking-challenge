# Yumi's 瞬発スピーキング（試作版）

## 使い方
`index.html` をブラウザで開きます。

- 30秒 × 5問
- 英語音声認識（Web Speech API / en-US）
- 認識ミスの手動修正
- Day 1〜7
- ブラウザ内に履歴保存
- 5問終了後、ChatGPTに貼りやすい形式でコピー

## 注意
音声認識はブラウザ側の Web Speech API に依存するため、端末・ブラウザによって利用可否や精度が異なります。
特に iPhone のブラウザでは挙動が異なる場合があります。

## GitHub Pagesで公開
GitHubに `index.html` をアップロードし、Repository Settings → Pages から main ブランチ/root を公開するとURL化できます。
