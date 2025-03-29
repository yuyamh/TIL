## 使用した教材
[【2024年最新】React(v18)完全入門ガイド｜Hooks、Next14、Redux、TypeScript](https://www.udemy.com/course/react-complete-guide/)
[React公式チュートリアル](https://ja.react.dev/learn)

## JS
- debugger;
debugger文を記述すると、この文で処理が止まる。
Chromeの開発ツールで検証可能。

- truthyとfalsy
  - falsy → 真偽値に変換した際に"偽(false)"とみなされる値のこと。
  - truthy → それ以外
 
  - falsyな値の一覧
    - false
    - 0 (数字)
    - 0n (big int)
    - "" (空文字)
    - null
    - undefined
    - NaN (Not a Number)

- 論理積（&&）と論理和（||）
  - && は 左側が false のときはそこで終了、すべて true の場合は 最後の値 を返す。
  - || は 左側が true のときはそこで終了、すべて false の場合は 最後の値 を返す。

## JSX
- JSファイルの中でHTMLタグライクにマークアップを記述可能。
- 若干の違いあり（className, htmlForなど）
- 1つのreturn内に1つのコンポーネントのみ許される（pタグ2つは不可）。
- Fragmentで囲むことで1つのコンポーネントとして扱うことが可能（<></>）
- XHTMLのように、必ず閉じタグをつける必要あり（\<br />　\<hr />など）。
