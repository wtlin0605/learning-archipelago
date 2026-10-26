# 學習歷程群島｜互動網站修正版

## 部署方式
1. 將 `index.html` 上傳至 GitHub repository `learning-archipelago` 的根目錄。
2. 覆蓋舊版 `index.html`，提交（Commit）變更。
3. 等待 GitHub Pages 重新部署。
4. 開啟網站後按 `Ctrl+F5` 強制重新整理；手機可重新載入或清除該網站快取。

## 修正內容
已修正 Three.js 與 OrbitControls 的模組匯入方式，避免 OrbitControls 因無法解析 `three` 模組而使整個互動程式停止。3D 場景仍需要連線至 jsDelivr CDN。
