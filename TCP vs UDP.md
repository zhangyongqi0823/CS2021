- 傳輸層主要兩個協定為：
  - (1)傳輸控制協定Transmission Control Protocol, TCP
  - (2)使用者資料元協定User Datagram Protocol, UDP
  
  
  傳輸控制協定（英語：Transmission Control Protocol，縮寫：TCP）(https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E6%8E%A7%E5%88%B6%E5%8D%8F%E8%AE%AE)
  是一種連接導向的、可靠的、基於位元組流的傳輸層通信協定
  TCP協定的執行可劃分為三個階段：連接建立(connection establishment)、資料傳送（data transfer）和連接終止（connection termination）
  
  
  使用者資料報協定（英語：User Datagram Protocol，縮寫：UDP)(https://zh.wikipedia.org/wiki/%E7%94%A8%E6%88%B7%E6%95%B0%E6%8D%AE%E6%8A%A5%E5%8D%8F%E8%AE%AE)
  UDP適用於不需要或在程式中執行錯誤檢查和糾正的應用，它避免了協定棧中此類處理的開銷。對時間有較高要求的應用程式通常使用UDP，因為丟棄封包比等待或重傳導致延遲更可取。
  由於UDP缺乏可靠性且屬於無連接協定，所以應用程式通常必須容許一些遺失、錯誤或重複的封包。

