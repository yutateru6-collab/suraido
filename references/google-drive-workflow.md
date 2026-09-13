# Google Drive連携ワークフロー

## 正本の場所
- Drive親フォルダ: `suraido`
  - Folder ID: `191889SVEc6AIzdRSeqBYfBJCEiHj_TFK`
  - URL: https://drive.google.com/drive/folders/191889SVEc6AIzdRSeqBYfBJCEiHj_TFK
- 背景素材: `suraido/backgrounds`
  - Folder ID: `16mhePGdZqJny9EgcQbfYG7ESD-7N8VIZ`
  - URL: https://drive.google.com/drive/folders/16mhePGdZqJny9EgcQbfYG7ESD-7N8VIZ

## Google Driveを使う英文法スライド作業の開始手順
1. このrepoの `SKILL.md` を読む。
2. `references/backgrounds.md` を読む。
3. Driveの `backgrounds` フォルダを一覧し、目的に合う画像を選ぶ。
4. 原則として既存素材を使う。背景を毎回新規生成しない。
5. 新規背景が必要な場合はbg01のデザインDNAを維持し、作成後Driveに追加する。
6. スライド作成後はレンダリングまたはサムネイルで全ページ確認する。

## 背景選択のルール
- デフォルトはbg01。
- ただし、すべてのページでbg01を使わない。
- 文法内容に応じて役割の合う背景を選ぶ。
- 5枚構成では2〜4種類を目安に使う。
- 同一画像の3枚以上連続使用は避ける。

## Google Slides / PowerPoint
- Google Slidesを直接編集する場合は、Google Drive / Slidesコネクタで既存素材を挿入する。
- PowerPointでクリック表示が必要な場合は、PPTX側で段階表示を設定してからDriveへ保存する。
- Google Slides側のAPIでアニメーション設定ができない経路では、アニメーションが付いたと偽らない。

## ファイル命名
- 文法スライド: `grammar_<topic>_<date>_v1`
- 背景: `bgNN_<role>.png`
- 改訂: `v2`, `v3` と上げる。`final_final` のような名前は避ける。

## 完了条件
- Drive上で対象ファイルが開ける
- 全ページの文字切れなし
- 背景と本文の干渉なし
- 文字サイズがstyle-guide準拠
- PowerPointのクリック表示を要求された場合、実際のクリック順を検証済み
