# source-monitor-varying-results-issue

**! This issue is now fixed as of [Source Monitor v3.5.3.327](http://www.campwoodsw.com/smbeta.html) !**

Reproduction details:
- Source Monitor v3.5.3.323 or v3.5.0.306
- Windows 7 Home Premium SP1 (x64)
- `ParseObject.java` test file taken from https://github.com/ParsePlatform/Parse-SDK-Android/blob/3441303006e0ae51c37a0008e4f891fb87afc2ee/Parse/src/main/java/com/parse/ParseObject.java

Steps:

1. Clone and run `run-source-monitor.bat` several times
2. Notice that details and summary results sometimes are different and produce high value (e.g. `1749250913`) complexity and/or line numbers (e.g. `7667823`)

See `sm-details-results-*.xml` and `sm-summary-results-*.xml` created using Source Monitor `v3.5.3.323` for sample results.
