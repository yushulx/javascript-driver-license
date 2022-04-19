# JavaScript Driver's License Scanner
The sample shows how to read and extract driver's license information from PDF417 using Dynamsoft [JavaScript barcode SDK](https://www.dynamsoft.com/barcode-reader/sdk-javascript/).

## Usage
1. Get a [free trial license](https://www.dynamsoft.com/customer/license/trialLicense?product=dbr) and update the following code:

    ```js
    Dynamsoft.DBR.BarcodeReader.license = "DLS2eyJoYW5kc2hha2VDb2RlIjoiMjAwMDAxLTE2NDk4Mjk3OTI2MzUiLCJvcmdhbml6YXRpb25JRCI6IjIwMDAwMSIsInNlc3Npb25QYXNzd29yZCI6IndTcGR6Vm05WDJrcEQ5YUoifQ==";
    ```
    
2. Deploy the project to a web server and then open the driver's license scanner in a web browser:
    
    ```bash
    python -m http.server
    ``` 

    ![JavaScript driver's license](https://www.dynamsoft.com/codepool/wp-content/uploads/2020/06/javascript-driver-license.png)

## Reference
- https://www.aamva.org/DL-ID-Card-Design-Standard/
- https://github.com/Dynamsoft/javascript-barcode/tree/master/example/web/decode-driver-license-for-AAMVA

## Blog
[Reading Driver’s License Information from PDF417 in JavaScript](https://www.dynamsoft.com/codepool/javascript-driver-license-pdf417-web.html)
