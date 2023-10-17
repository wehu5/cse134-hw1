## Part 1
### Q1 Introduction to Web Technologies
![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\deployscreenshot.png)
Link: https://master--imaginative-starburst-050db0.netlify.app

-----
### Q2 Chrome DevTools - Network
1. \# of Requests by Content Type
- HTML: 1
- CSS: 1
- JS: 1
- Font: 1
- GIF: 1
- JPG: 2 
- PNG: 1
2. Total # of Requests
28 requests
3. Total Bytes Sent
6.7 megabytes
4. Waterfall of Requests Screen Capture
![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\waterfall.png)

-----
### Q3 Client-Side Inherently Insecure Demo
![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\q3.png)

-----
## Part 2
1. Were any parts of navigating ESPN site easy? Were any parts difficult?
Easy: It was easy to go through every item. Therefore, I just have to wait until I hear **Top Headlines**.
Difficult: It took me a long time to hear **Top Headlines** because it is located at a far right corner.
2. Were any parts of navigating webaim.org's site easy? Were any parts difficult?
Easy: It was quick to find the answer about archive once the page is correct.
Difficult: There are many similar terms that sound like *Web Accessibility Virtual Training*, and there are many links included in these clickable links. It was easy to enter other pages that do not have the information about archive classes.

-----
## Part 3
### Q1 HTTP Response headers
**1. UCSD:**
![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\ucsdresponseheader.png)
**2. UCI:**
![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\uciresponseheader.png)
**3. What is troubling about the UCI response HTTP headers?**
In the server section, it is exposing the server's information. This is an information disclosure issue that could be troubling to the UCI website if someone wants to do something malicious to the page.

-----
### Q2 JavaScript Off
1. ![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\mergeucsdjs.png)

-----
2. One obvious broken feature is the search button located top right of the page. When JS is disabled, clicking the magnifying glass pattern does nothing. Also when the website is shrunk to point when the "topics" such as *ABOUT, ACADEMICS, ADMISSIONS AND AID, etc*, are not displayed and they are only visible if the drop down button is clicked, the drop down button does not show the "topics" with JS disabled.

-----
3. ![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\mergescrippsjs.png)

-----
4. When JS is disabled, all of the contents in the Scripps page are gone, only a blank page is left.

-----
5. ![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\mergeuclajs.png)

-----
6. The website of UCLA is partially functioning when JavaScript is disabled: most of the content are still visible and clickable; clicking to the buttons or links can still redirect the page to the designated page; however, in the middle of the page, the page loses its visuals and leaves a blank in between the contents.

-----
### Q3 Custom vs. Default 404 Pages
1. Yes
2. Link: https://www.csuci.edu/programs
3. No
4. Link: https://jpcatholic.edu/admissions
5. Users tend to have no idea about what a default 404 page means. They could think that the problem is on their end since the default 404 page is not informative; whereas a custom is way more informative and interactive, as seen from the csuci page. The users then would know what the problem is and continue their browsing on the page.

-----
### Q4 Search Engines - robots.txt
1. Yes.
![image](C:\Users\11029\OneDrive\文档\UCSD_Classes\CSE134B\cse134-hw1\nytrobotstxt.png)
2. While robots.txt blocks search engine crawlers, it discloses information about the pages that the owner wants to hide from the others. Then robots.txt can reveal hidden information that is not intended for the public.
3. The nytimes.com tries to block User-agents: CCBot, Google-Extended, GPTBot, ia_archiver, omgili, omgilibot, and Twitterbot. Such bots attempt to extract contents from the internet to researchers, companies, and individuals for their purposes at no cost. Since NY Times require subscription for its content, such bots are then blocked.

-----
### Q5 Search Engines - Google Hacking
