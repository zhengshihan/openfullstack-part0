```mermaid
sequenceDiagram
    participant browser
    participant server
Note right of browser: User enters information and clicks save button
Note right of browser: Browser pushes the new entry to list
 browser->>server: Post https://studies.cs.helsinki.fi/exampleapp/new_note_spa 

    activate server
    deactivate server
Note left of server: Server receives data
   
```
