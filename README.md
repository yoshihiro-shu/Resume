# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|朱　義宏 (Yoshihiro Shu)|
|Qiita|[yoshihiro-shu](https://qiita.com/yoshihiro-shu)|
|Twitter|[よっしー@エンジニア](https://twitter.com/iamyoshitter)|

## スキル
### 言語

[![My Skills](https://skillicons.dev/icons?i=go,py,js,ts)](https://skillicons.dev)

### フレームワーク

[![My Skills](https://skillicons.dev/icons?i=vue,nuxtjs,django)](https://skillicons.dev)

### その他

[![My Skills](https://skillicons.dev/icons?i=postgres,redis,linux,docker,kubernetes,gcp)](https://skillicons.dev)

## 言語

- 日本語
  - ネイティブ
- 英語
  - ニュージーランドに一年留学をしていた
  - 留学時アルバイトをしていたのでビジネス英語も可
- 中国語
  - リスリングのみ可能

## 強み

- 積極性

- 探究心が強い
  - 盆栽（自宅サーバー）を構築し、Kubernetesの知見を深めている

- 現状に満足しない向上心

## やったことはないが興味があるもの

- React, Nextjsによるフロントエンドの開発

- Github Actionを使った、CIの自動化

- イベントなどの運営

## 職務経歴

### 株式会社ZUU(インターン:2022/02-2022/04, 正社員:2022/04-)

職種: フルスタックエンジニア

自社メディアとその技術基盤を他社にワンストップで提供する事業の保守運用開発を行なっています。

#### 1.自社製品のリプレイス開発(2022/02-)

自社製品であるCMSのリプレイス開発に従事

- Csrf Token Securityの新規開発と会員機能リプレイス開発に従事

- Kubernetesを用いて、`ManegedCertificate`の開発（https通信を行うための、マネージド証明書の自動管理機能）
<!--   - 既存のシステムにおいて証明書の管理を`cert-manager`で開発されていたものを、`ManegedCertificate`にリプレイス開発を行なった。
  - HelmのValues.yaml(設定ファイル)による柔軟なカスタマイズを行えるように開発した。 -->

|使用技術|使用サービス or フレームワーク|
|---|-----|
|Golang|echo|
|JavaScriot|NuxtJs|
|Infrastructure|Docker, Kubernates, GCP|
|CI tool|GitHub Actionによるビルドテスト|
|CD tool|Argo CD|

#### 2.自社製品のリリース作業(2022/06-2022/08)

リプレイス開発したソフトウェアのリリースとドキュメント化

- terraformとKubernetesを用いてリリース作業及びドキュメント化 

|使用技術|使用サービス or フレームワーク|
|---|-----|
|Amazon Web Service|Route53|
|Google Cloug Platform|GKE, Load Balancer, Cloud Armor, Cloud Storage, Static IPAddress, Uptime Checks, Alert Policy|
|terraform|上記のGCPサービスの実装|
|Kubernates|Ingress, Service, Deployment, ConfigMap, CronJob, Job, ManagedCertificate|
|CI tool|GCP Cloud BuildによるDocker Imageの自動ビルド|

#### 3.広告収益管理の自動化(2022/10-)

収益管理の自動ツールの開発・保守・運用

背景
- 毎月実施しているメディアの広告収益の　管理の自動化

|使用技術|使用サービス or フレームワーク|
|---|-----|
|Python|Pandas|
|Google Cloug Platform|Big Query, Cloud Function, GCS, Alert Policy|
|terraform|上記のGCPサービスの実装|
|CI tool|GitHub Actionsによるterrformの自動化テスト|
|CD tool|Argo CD|

#### 4.ヘルプサービスの開発(2023/02-)

社内システムのヘルプサービスの開発

- 要求定義、要件定義、システム設計、開発、保守運用まで担当

|使用技術|使用サービス or フレームワーク|
|---|-----|
|CMS|[hugo](https://gohugo.io/hosting-and-deployment/hosting-on-github/)|
|Amazon Web Service|Route53|
|Google Cloug Platform|GKE, Load Balancer, Cloud Armor, Cloud Build|
|terraform|上記のGCPサービスの実装|
|CI tool|GCP Cloud Buildによる、Docker Imageの自動ビルド|
|CD tool|Argo CD|

### アイタックソリューションズ株式会社（バイト:2021/09-2022/01）

職務: サーバーサイドエンジニア

#### 混雑状況判定システム

- 管理画面をPythonのDjangoを用いて実装

## 課外活動

<!-- ### 社外プロジェクト
* [運営に携わっているコミュニティ](そのコミュニティのconnpassやカンファレンスページのリンクとか)
* [副業で携わっているサービス](そのサービスのランディングページのリンクとか) -->

<!-- ### 過去の登壇資料
* [Speaker Deck](Speaker Deckの自分の資料のページとか)
 -->
<!-- ### 受賞歴
* [イベント名と受賞した賞](イベントのランディングページのリンクや、結果がわかる記事など) -->

### 執筆歴
* [Qiita](https://qiita.com/yoshihiro-shu)
