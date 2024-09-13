# 🎉 **FunC 中文研習資源庫**

歡迎來到 **FunC 中文研習資源庫**！這個倉庫旨在為希望學習並掌握 FunC 語言及其應用的中文開發者提供資源和範例。我們匯集了關於 FunC 語言的基礎知識、進階技巧以及實際應用示例，幫助開發者在 Telegram Open Network (TON) 區塊鏈上開發高效能的智能合約。

🚀 **本資源庫將不斷更新，添加更多學習資源和實踐範例！**

## 📚 **中文註解代碼目錄**
- ### FunC 標準工具庫 - [代碼](https://github.com/wyc-dev/func_zh/blob/main/contracts/stdlib_zh.fc) / [PDF](https://github.com/wyc-dev/func_zh/blob/main/readable_pdfs/stdlib_zh.pdf)
  *根據 stdlib.fc 作中文註解編譯，包含 FunC 標準函式庫的完整代碼，主要負責內聯 Fift 編碼組成基礎功能， 適合引用於大部份 TON 智能合約開發。*
  
- ### 第五代 TON 錢包 - [代碼](https://github.com/wyc-dev/func_zh/blob/main/contracts/wallet_v5_zh.fc) / [PDF](https://github.com/wyc-dev/func_zh/blob/main/readable_pdfs/wallet_v5_zh.pdf)
  *根據 wallet_v5.fc 作中文註解編譯，是第五代 TON 錢包的最新版合約，以 extension 取替 v4 的 plug-ins，讓用戶在區塊鏈上執行安全高效的資金管理。*

- ### Jetton 代幣主合約 - [代碼](https://github.com/wyc-dev/func_zh/blob/main/contracts/jetton-minter_zh.fc) / [PDF](https://github.com/wyc-dev/func_zh/blob/main/readable_pdfs/jetton-minter_zh.pdf)
  *根據 jetton-minter.fc 作中文註解編譯，用於創建和管理 Jetton 代幣的主合約，包含代幣鑄造和分發的功能。*

- ### Jetton 錢包構建 - [代碼](https://github.com/wyc-dev/func_zh/blob/main/contracts/jetton-uilts_zh.fc) / [PDF](https://github.com/wyc-dev/func_zh/blob/main/readable_pdfs/jetton-uilts_zh.pdf)
  *根據 jetton-uilts.fc 作中文註解編譯，提供了如何構建和操作 Jetton 代幣錢包的實際代碼和工具，適合需要管理代幣的開發者。*

- ### 鏈上費用計算 - [代碼](https://github.com/wyc-dev/func_zh/blob/main/contracts/gas_zh.fc) / [PDF](https://github.com/wyc-dev/func_zh/blob/main/readable_pdfs/gas_zh.pdf)
  *根據 gas.fc 作中文註解編譯，涵蓋了如何計算智能合約在 TON 區塊鏈上執行的費用，包含 Gas 預計和存儲費用運算的相關代碼。*

- ### 操作碼定義及工作鏈識別 - [代碼](https://github.com/wyc-dev/func_zh/blob/main/contracts/op-code_workchain_zh.fc) / [PDF](https://github.com/wyc-dev/func_zh/blob/main/readable_pdfs/op-code_workchain_zh.pdf)
  *根據 op-code.fc 及 workchain.fc 作中文註解編譯，詳細解釋 Jetton 錢包的操作碼定義和工作鏈識別的函數應用，通常用於 Jetton 智能合約開發的邏輯。*


## ✨ **介紹**
FunC 是 Telegram Open Network (TON) 使用的主要智能合約語言。它設計為一種簡潔且高效的編程語言，專注於在 TON 區塊鏈上執行的合約中提供高度安全和可靠性。本資源庫專門針對中文使用者，旨在降低學習曲線並推動 FunC 的社區發展。

## 📂 **資源列表**
本倉庫目前包含以下資源：

1. **FunC 標準函式庫中文導讀** (`readable_pdfs`)：路徑提供了 FunC 標準函式庫的 PDF 說明文檔，詳細解釋函數的使用方法和原理。
2. **FunC 標準函式庫源代碼配中文註解** (`contracts`)：這是 FunC 標準函式庫的實際源代碼，附上詳細中文註解。

## 💻 **如何使用**
1. 克隆此倉庫到你的本地環境：
    ```bash
    git clone https://github.com/yourusername/func-zh-repo.git
    ```

2. 瀏覽資源文件，開始學習 FunC 語言及其應用。推薦先閱讀 `stdlib_zh.pdf` 以瞭解標準函式庫的內容，再根據 `stdlib_zh.fc` 進行實際的編碼練習。

3. 將本資源庫作為你的 FunC 開發項目的參考指南，不斷深入學習和探索。

## 🤝 **貢獻指南**
我們歡迎社區的每一位成員對此資源庫的貢獻。如果你希望添加新的資源、修正錯誤或改進現有內容，請參考以下步驟：

1. Fork 此倉庫並創建你的分支：
    ```bash
    git checkout -b new-feature-branch
    ```

2. 提交你的更改：
    ```bash
    git commit -m "Add new resource or fix bug"
    ```

3. 推送到你的分支：
    ```bash
    git push origin new-feature-branch
    ```

4. 提交一個 Pull Request，並描述你的更改內容。

## 📜 **許可協議**
本倉庫的內容基於 MIT 許可協議開源。詳細信息請參閱 [LICENSE](LICENSE) 文件。

