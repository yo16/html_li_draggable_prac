# html_li_draggable_prac
li要素をドラッグして順番を移動するサンプル

## 概要
- 各`li`に、`draggable="true"`を設定する
- `li`の親要素である`ul`に`dragstart`、`dragover`、`dragend`のイベントを`addEventListener()`して、適切に`insertBefore()`で移動させる

