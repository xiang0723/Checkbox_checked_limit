# Checkbox_checked_limit
使用 jQuery 來控制 Checkbox 選取上限

範例：
https://blias.com/xiang/demo/jq_checkbox_limit/

# 使用說明
### 每一個 Checkbox 群組結構請依照以下範例設定：
```HTML
  <div id="(自訂不重複使用的id名稱，例如 Group_A)" class="checkbox_group_limit" limit="(此 Checkbox 群組選取上限值，填入正整數即可 例如:3)">
    <h3>最多選(自訂標題) <span class="limit">N</span> <span class="checkbox_counts"></span><span class="show_message"></span></h3>
    <div class="checkbox_row"><input type="checkbox" value="(自訂內容)"><label >(自訂內容)</label></div>
    <div class="checkbox_row"><input type="checkbox" value="(自訂內容)"><label >(自訂內容)</label></div>
    ...(依需求增減項目)
  </div>
```
範例中 () 的內容均可自訂或依需求改變，最主要的是最外圍的 <div> id 值不可重複命名。
