# Andy的飲料訂購系統

## 開發起因
在公司與同事一起訂飲料時，經常遇到在群組中手動輸入訂單資訊格式不統一的問題，導致統計困難，甚至容易出錯。因此，為了提高點餐效率，減少錯誤，開發了這個飲料訂購系統，讓所有人可以透過統一的格式提交訂單，並自動記錄與導出訂單資料。

## 功能特色
**選擇店家與飲品**：可從多家飲料店的選單中選擇飲料，避免手動輸入錯誤。
**個人化訂購**：可填寫姓名、選擇甜度，並加入備註需求。
**自動儲存訂單**：當天訂單會自動保存在本地儲存 (localStorage)，下次開啟網頁時可繼續查看。
**下載訂單Excel檔**：系統會自動將當天訂單匯出成 Excel，方便整理與分享。
**清除訂單**：可一鍵清空訂單，避免累積過多舊資料影響查閱。
**即時更新訂單列表**：每次提交訂單後，畫面會即時更新當日訂單，方便查看訂購狀況。

## 使用方式
1. **輸入姓名**：必填。
2. **選擇店家**：系統會自動載入該店家的飲料選單。
3. **選擇飲料與甜度**。
4. **填寫備註**（可選）。
5. **提交訂單**：系統會將訂單儲存並更新訂單列表。
6. **下載訂單**：訂單自動存為 Excel 檔案，方便記錄與傳送。
7. **清空訂單**：清除所有訂單紀錄。

## 技術架構
- **HTML**：前端頁面結構。
- **CSS**：基本樣式設計。
- **JavaScript**：處理訂單提交、儲存與下載。
- **LocalStorage**：儲存當日訂單紀錄。
- **XLSX.js**：用於將訂單匯出為 Excel 檔案。

## 文件結構
```
├── order.html  # 主頁面
├── README.md   # 本說明文件
```

## 未來改進方向
- 支援多筆訂單刪除功能。
- 允許使用者自訂飲料品項。
- 增加訂單搜尋與篩選功能。
