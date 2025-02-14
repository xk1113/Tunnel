Usage:
• To collect server logs for analysis: 

./MSTDiagnos collectlogs

• To troubleshooting some common issue(current I only add one scenario - to test the internal website connectivity

./MSTDiagnos testconn <URI>

Logs collected:

    ##collect history command
    ##collect iptables rules
    ##collet processes
    ##collect agent certificate
    ##collect files in /etc/mstunnel except private folder(so private key is not saved)
    ##collect files in /tmp/mstunnel folder if it exists
    ##collect server logs


Example to troubleshooting connectivity to Internal Websites:
![image](https://github.com/user-attachments/assets/0d2986fd-2738-4356-80a3-9d4913335555)


