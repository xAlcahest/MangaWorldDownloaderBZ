# MangaWorld Downloader 
A Downloader For mangaworld.in,
a project for educational purposes not affiliated with mangaworld.in (now with the .bz tld), I am not responsible for the use and images hosted on mangaworld.in (now with the .bz tld)

# Features
- Download of whole manga or single chapters
- MultiThreaded Download for downloading pages at maximum speed
- Preview Download
- In the releases, a bulk download script is provided

# In case of a CloudFlare captcha
To pass the block the program needs the cf_clearance cookie and the useragent of the browser you used to solve the captcha

- Token: Solve the captcha on www.mangaworld.in and in Dev Console get the value of the cf_clearance cookie
  ![Token](https://i.imgur.com/HYUu0M0.png)

- UserAgent: At www.whatsmyua.info you can see your useragent
  ![Useragent](https://i.imgur.com/nZZfCt1.png)

the program will automatically ask you for these two parameters if it needs them, then it will automatically save them in a JSON file so you can use them
even after the program has been closed.

Manually: you can manually enter the values in a file called `cred.json` with this structure in the same folder as the executable

```
{
"useragent" : "useragent value here"
"cf_clearance" : "cf_clearance value here"
}
```

