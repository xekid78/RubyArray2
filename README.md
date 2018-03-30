# RubyEachWithIndexMethod
`each_with_index()`メソッド

## 処理
配列の内容を`Array()`クラスの`each_with_index()`メソッドを使って出力します。

## コード
```
enemies = ["スライム", "モンスター", "ゾンビ", "ドラゴン", "魔王"]
enemies.each_with_index do |person, i|
    puts "#{i + 1}番目の#{person}が現れた"
end
```

## 出力結果
```
1番目のスライムが現れた
2番目のモンスターが現れた
3番目のゾンビが現れた
4番目のドラゴンが現れた
5番目の魔王が現れた
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
