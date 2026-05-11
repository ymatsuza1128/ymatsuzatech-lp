# Privacy Policy / プライバシーポリシー

**GitNote**  
Last updated: 2026-05-11

---

## 日本語

### 1. 収集する情報

GitNote が収集・保存する情報は以下のみです。すべてお使いの端末内にのみ保存されます。

| 情報 | 用途 | 保存場所 |
|------|------|----------|
| GitHub OAuth アクセストークン | GitHub リポジトリへの読み書き認証 | 端末内（Android Keystore で暗号化） |
| リポジトリ URL・ブランチ名 | クローン・同期先の特定 | 端末内（DataStore） |
| Git コミット用の著者名・メールアドレス | コミットメタデータへの記録 | 端末内（DataStore） |
| Markdown ファイル | ノートの表示・編集 | 端末内（アプリ専用ストレージ） |

### 2. 収集しない情報

- 位置情報
- 連絡先・カメラ・マイクなどのセンサーデータ
- 広告 ID・デバイス識別子
- アプリの利用状況・クラッシュレポート（分析 SDK は組み込んでいません）

### 3. 第三者への提供

GitNote はいかなる個人情報も第三者に提供・販売しません。

アプリが通信する外部サービスは以下のみです。

- **GitHub API**（`api.github.com`）: リポジトリ一覧の取得・認証
- **ユーザー自身の GitHub リポジトリ**: ノートファイルの同期

これらの通信はすべて HTTPS で行われます。

### 4. データの管理・削除

- アプリをアンインストールすると、端末に保存されたすべてのデータ（トークン・設定・クローン済みファイル）は削除されます。
- GitHub アカウントとの連携を解除するには、[GitHub の設定画面](https://github.com/settings/applications) から GitNote のアクセス許可を取り消してください。

### 5. お問い合わせ

プライバシーに関するご質問は、GitHub の [Issues](https://github.com/ymatsuza1128/github-markdown/issues) またはリポジトリ記載のメールアドレスまでご連絡ください。

---

## English

### 1. Information We Collect

GitNote collects and stores only the following information, all of which is stored locally on your device.

| Data | Purpose | Storage |
|------|---------|---------|
| GitHub OAuth access token | Authenticate read/write access to GitHub repositories | Device only (encrypted via Android Keystore) |
| Repository URL and branch name | Identify clone/sync target | Device only (DataStore) |
| Git author name and email | Git commit metadata | Device only (DataStore) |
| Markdown files | Display and edit notes | Device only (app private storage) |

### 2. Information We Do Not Collect

- Location data
- Contacts, camera, microphone, or other sensor data
- Advertising IDs or device identifiers
- Usage analytics or crash reports (no analytics SDK is included)

### 3. Sharing of Information

GitNote does not share or sell any personal information to third parties.

The only external services the app communicates with are:

- **GitHub API** (`api.github.com`): Repository listing and authentication
- **Your own GitHub repositories**: Note file synchronization

All communication is conducted over HTTPS.

### 4. Data Deletion

- Uninstalling the app removes all locally stored data (token, settings, cloned files) from your device.
- To revoke GitNote's access to your GitHub account, visit [GitHub Settings → Applications](https://github.com/settings/applications) and revoke GitNote's authorization.

### 5. Contact

For privacy-related questions, please open an [Issue](https://github.com/ymatsuza1128/github-markdown/issues) or contact us via the email address listed in the repository.
