<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Table with Header & Foot</title>
</head>
<body>
    <header bgcolor="blue" style="color: blue; text-align: center; padding: 20px;">
        <h1>Table Tag & Atribute Page</h1>
    </header>

    <h2>একটি সাধারণ টেবিল</h2>
    <table border="1">
        <tr>
            <th>ক্রমিক নং</th>
            <th>নাম</th>
            <th>বয়স</th>
        </tr>
        <tr>
            <td>১</td>
            <td>রহিম</td>
            <td>২৫</td>
        </tr>
        <tr>
            <td>২</td>
            <td>করিম</td>
            <td>৩০</td>
        </tr>
        <tr>
            <td>৩</td>
            <td>সুমন</td>
            <td>২২</td>
        </tr>
    </table>
    
    <h2>কলস্প্যান এবং রোস্প্যান সহ টেবিল</h2>
    <table border="1">
        <tr>
            <th rowspan="2">ক্রমিক নং</th>
            <th colspan="2">ব্যক্তিগত তথ্য</th>
        </tr>
        <tr>
            <th>নাম</th>
            <th>বয়স</th>
        </tr>
        <tr>
            <td>১</td>
            <td>রহিম</td>
            <td>২৫</td>
        </tr>
        <tr>
            <td>২</td>
            <td>করিম</td>
            <td>৩০</td>
        </tr>
    </table> 
    <br>

    <h2>বিভিন্ন সাইজ ও কালারের টেবিল </h2>
    <table border="1" cellpadding="10" cellspacing="0" width="100%">
        <tr>
            <th width="20%" bgcolor="#ffcccc">ক্রমিক নং</th>
            <th width="30%" bgcolor="#ccffcc">নাম</th>
            <th width="50%" bgcolor="#ccccff">বয়স</th>
        </tr>
        <tr>
            <td height="50" bgcolor="#ff9999">১</td>
            <td height="70" bgcolor="#99ff99">রহিম</td>
            <td height="90" bgcolor="#9999ff">২৫</td>
        </tr>
        <tr>
            <td height="60" bgcolor="#ff6666">২</td>
            <td height="80" bgcolor="#66ff66">করিম</td>
            <td height="100" bgcolor="#6666ff">৩০</td>
        </tr>
        <tr>
            <td height="70" bgcolor="#ff3333">৩</td>
            <td height="90" bgcolor="#33ff33">সুমন</td>
            <td height="110" bgcolor="#3333ff">২২</td>
        </tr>
    </table> 
    <footer bgcolor="black" style="color: Green; text-align: center; padding: 10px; margin-top: 20px;">
        <p>&copy; 2025 আমার ওয়েবসাইট</p>
    </footer>

</body>
</html>
