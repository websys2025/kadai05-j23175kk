## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
    エンドポイント（"https://zipcloud.ibsnet.co.jp/api/search"）
    郵便番号を入力するとその番号の住所を返すAPI
* リクエストとレスポンスのフォーマット
    リクエストのフォーマット（例："https://zipcloud.ibsnet.co.jp/api/search?zipcode=2640025）
    レスポンスのフォーマット（例："千葉県 千葉市若葉区 都賀"）
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
    Wikipedia REST API（" https://ja.wikipedia.org/api/rest_v1/"）
* エンドポイントと機能
    エンドポイント（"https://ja.wikipedia.org/api/rest_v1/page/summary"）
    入力された単語のの要約をWikipediaページの内容を要約して返すAPI
* リクエストとレスポンスのフォーマット
    リクエストのフォーマッ（例："https://ja.wikipedia.org/api/rest_v1/page/summary/富士山"）
    レスポンスのフォーマット（例："富士山は、日本の本州中南部に位置する活火山である。"）
### Q3-3. 感想
* 今回の課題で苦労したこと
    まずAPI自体について理解が浅かったためそこから理解するというのが苦労した。
* 演習を通して理解できたこと
    無料のAPIをJavaScriptを使ってデータを取得し、HTMLで表示させることを理解した。
* Web APIの利便性や課題など
    APIを活用することで他のサービスから簡単に情報を取得することができる。
    javaScriptの理解がないとWebAPIをうまく活用できないのは今後の課題だと考える。
