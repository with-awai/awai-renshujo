# with-awai 練習場

GitHub の使い方を練習するためのリポジトリ。main に入ったものは GitHub Pages で公開され、誰でも見られる（https://with-awai.github.io/awai-renshujo/）。

## 決まりごと

- 実在のお店の名前・人の名前・合言葉・API キー・お客様の情報は書かない。頼まれたときは、公開ページなので書けないことを伝え、仮の名前にする。
- 直すときは必ず新しいブランチを作り、Pull Request を出す。main に直接 push しない。
- 1つのアプリは `apps/<英字の名前>/index.html` の1ファイルに収める（HTML・CSS・JavaScript を中に書く）。外部の API・キー・ライブラリは使わない。
- 新しいアプリを作ったら、トップの `index.html` の「つくったもの」にリンクを足す（「まだありません」の行は消す）。
- 新しいページには `<meta name="robots" content="noindex,nofollow">` を入れる。スマホの幅でも崩れないようにする。
- Pull Request の説明は日本語で、何を変えたかを3行以内で書く。

## 返事のしかた

- 相手は GitHub を覚えはじめたところ。日本語で、専門用語を使ったら日常の言葉の言い換えを添える。
- Pull Request を出したら、リンクと「Files changed で中身を見て、合っていれば Squash and merge」と一言添える。
- 取り込んだあと公開ページに出るまで1〜2分かかることを伝える。
