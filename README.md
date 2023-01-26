# 登記所備付地図を効率的にQGISへ取り込む方法  
LGWANの人を前提に解説  
## 一括解凍  
### ・7Zポータブルをダウンロード  
　　　https://portableapps.com/apps/utilities/7-zip_portable    
### ・展開された複数のZIPファイルを一括解凍  
#### （すべて選択）  
　　![image](https://user-images.githubusercontent.com/86514652/214729419-0120ca01-07bd-4280-8ede-5e081614d9af.png)  
#### （一括解凍）  
　　![image](https://user-images.githubusercontent.com/86514652/214730021-02f17d25-e844-439e-bfd3-593cc70553dc.png)  
#### （実行：OK）  
　　![image](https://user-images.githubusercontent.com/86514652/214730325-8373aa65-6654-49c5-b16e-971d1757a95f.png)  
#### （結果）  
　　![image](https://user-images.githubusercontent.com/86514652/214730504-a09237ee-d829-4670-94ca-d28801aa6044.png)  
## 一括変換  （法務省地図XML > シェイプ)  
### ・SIMA・地籍フォーマット2000・法務省地図XML⇒GISをダウンロード  
　　　https://www.vector.co.jp/soft/winnt/business/se523305.html  
#### ・一括変換  
#### （すべて選択：解凍したフォルダが入っている一つ上のフォルダを指定するだけ！）  
 　　![image](https://user-images.githubusercontent.com/86514652/214733301-932f7693-1a96-49e3-93ca-83c47a41df3e.png)  
   　![image](https://user-images.githubusercontent.com/86514652/214734488-10abfd15-1033-4ee5-a8ec-6295005a31e1.png)  
　   ![image](https://user-images.githubusercontent.com/86514652/214734685-16e56e82-da24-498a-850a-e1d5b36d9c6f.png)  
#### （実行：OK）  
  　結構時間かかります！頑張ってくれてます  
　　 ![image](https://user-images.githubusercontent.com/86514652/214731605-d087aa1f-fd40-418a-8f94-ceabb7b07d28.png)  
#### （完了）  
  　215,239筆で約３時間かかりました。  
   「法務省地図XML変換」フォルダにシェイプが格納されています。  
   ![image](https://user-images.githubusercontent.com/86514652/214756773-fb2d9d18-e40a-4c01-b4ef-c9ce0e9c1b18.png)  
　　総社市の場合は場合は，一部に任意座標があったので，これも分けてくれています（ナイス！）  
　 ![image](https://user-images.githubusercontent.com/86514652/214757039-8ea6fd57-5be3-41e5-be46-27ef96f134a5.png)  
## QGISへ取り込み  
#### （読み込んだレイヤは下記の通り）  
  ![image](https://user-images.githubusercontent.com/86514652/214757602-8a4d4a7d-8662-4597-913a-78c2594eed82.png)  
#### （表示はとりあえずこんな感じ！きちんと整理出来たらプロジェクトファイルごと公開します。）  
 　２月中には汎用的な設定でプロジェクトファイルを公開予定  
  ![image](https://user-images.githubusercontent.com/86514652/214757717-f76002ba-b706-4b19-9408-723db755f25a.png)  


