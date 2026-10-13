# 喵咪日常 v1.7.5｜真實貓咪聲音版

## 更新 GitHub Pages
將此資料夾內的 `index.html`、`sounds/` 資料夾與 `.nojekyll` 放到 `neko-daily` 專案根目錄，使用 GitHub Desktop Commit 並 Push。

**請先從舊版本匯出 JSON 備份。** 保留原本的 `localStorage` 存檔鍵 `neko_daily_v01` 及存檔格式 3。更新網頁與重新領養是不同操作。

## 真實貓叫錄音
玩家上傳四個 Mixkit WAV：Sweet kitty meow、Domestic cat hungry meow、Little cat attention meow、Cartoon kitty begging meow。
本版轉為 MP3 並小幅平衡音量，儲存在 `sounds/*.mp3`。本版 HTML 同時內建同一組 MP3 的備援資料，單檔 HTML 在離線狀態仍能播放四種真實喵叫。

音效使用須遵守 Mixkit Sound Effects Free License：
https://mixkit.co/license/#sfxFree
不可單獨轉售或作為素材庫再散布音效。

## 操作與限制
* 進入「音效與真實貓叫」可分別試聽四種叫聲。
* 某些瀏覽器禁止沒有使用者互動的自動播放，請先按試聽、餵食或玩耍啟動音效。
* 原呼嚕聲仍依賴 Wikimedia 外部錄音；與這次整合的四種離線喵叫不同。
* 版本號為 v1.7.5；保留原有雙房間、落地窗、NVDA 按鈕操作、存檔安全性。
