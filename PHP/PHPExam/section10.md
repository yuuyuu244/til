# 10.ユーザの記憶：クッキーとセッション

## クッキーとセッション

- クッキーとはWebサーバとPHPに対する特定のWebクライアントを識別するために利用される
- セッションとはショッピングカート情報など複数の値を継続して保持するような場合に利用される

## setcookie()関数

- クッキーを定義する
- setcookie(name, expire, path, domain, secure, httponly)
- name・・・クッキーの名前
- value・・・クッキーの値
- expire・・・クッキーの有効期限
- path・・・URLパスの指定
- domain・・・クッキーが有効なドメインの指定
- secure・・・secure属性の指定
- httponly属性の指定

## PHPSESSID

- セッションが利用するクッキーの値

## session_start()

- セッションを開始する

## session_destroy()

- セッションのデータを破棄する
