# 概要
掲示板アプリ。
認証は不要。  
話題のことをトピックと呼ぶ。  
トピックに対しての返信をコメントと呼ぶ。

## トピックについて
タイトル、作成者名、その本文で構成される。

## コメントについて
トピックに対してコメントをする。  
コメントに対してコメントをすることはできるが、  
トピックに対してほどの強い参照制約はない。
つまりコメント先のコメントが削除されても、そのコメントへのコメントは削除されることがない。

作成者名と本文で構成される。

## 作成者について
作成者は匿名で一意に識別されることはない。

# Gitのお約束
作業をするときはmasterブランチ以外のブランチで作業します。  
またブランチを切るときは  
future/自分のユーザー名/実装する機能名  
のようなブランチ名にします。
具体的には私の場合でComment一覧機能を実装する場合は以下のようになります。  
future/kinoshita/Comment一覧  
Pushする場合はmasterに**しないでください**  
一度現在のブランチ名でpushしてから、  
pullリクエストをGitHub上で作成してください。  
masterへのマージはメンバーが確認しコードレビューをしてからおこないます。  


