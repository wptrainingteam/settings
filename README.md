# Settings

## Description

In this lesson you will learn what the first steps in configuring the WordPress Dashboard>Settings area of your WordPress website will be. This walkthrough will give you an understanding of the options in the Settings tab and the basics of your website.

## Objectives

After completing this lesson, you will be able to:

*   Configure the basic settings of your WordPress website.
*   Identify/assign the Home page of your website.
*   Identify/assign the Blog page of your website.
*   Control user privileges for access and commenting on your website.
*   Explain what a permalink is and how to select the best structure for your website pages/posts.

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Basic knowledge of how to log in to your [WordPress Dashboard](https://make.wordpress.org/training/handbook/user-lessons/overview-of-the-dashboard/) > Settings area
*   Understanding of WordPress [pages and posts](https://make.wordpress.org/training/handbook/user-lessons/pages-vs-posts/)

## Assets

*   You need to have WordPress installed on a local or live hosting server.

## Screening Questions

*   Are you familiar with the difference between a page and a post in WordPress?
*   Have you thought about how you want your website to be structured? (Do you want your blog posts featured on your home page, or on a separate "Blog" page?)
*   Do you want anyone to be able to register on your site and comment on your posts, or do you want to control user registration and comments?

## Teacher Notes

*   **Time estimate:** 30 minutes
*   Performing a live demo and/or having students accessing their Settings during the lesson will be helpful in their understanding of the Settings options.
*   A live install of WordPress should work fine for this lesson. A local install is also acceptable.

## Hands-on Walkthrough

### Introduction: Welcome to WordPress!

In this lesson you will learn the first steps in setting up the basic structure of your WordPress website. These settings will determine the page and post structure, users, commenting, and media settings to ensure that your website functions globally the way you intend it to. [![This is a screenshot of the Settings in the WordPress Dashboard](https://make.wordpress.org/training/files/2014/12/WordPressSettings-1024x459.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressSettings.jpg) From the WordPress Dashboard, locate the Settings menu. You will see the following options when you hover over this item: General, Writing, Reading, Discussion, Media, Permalinks.

### Step one: General Settings

**[![This is a screenshot of the General Settings in the Admin Screen in WordPress](https://make.wordpress.org/training/files/2014/12/WordPressGeneralSettings-724x1024.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressGeneralSettings.jpg)** **Site Title and Tagline:** If you did not set these up when you installed WordPress, or if you would like to change or redefine these items, change them here. By default, WordPress includes “just another WordPress site” as your site’s tagline. Use descriptive language for your website here, as search engines will display this information prominently. The theme you select may or may not display the Tagline. **URL Settings:** The URL settings for your website, WordPress Address and Site address, should be set up automatically with your WordPress install and are rarely changed in this Settings area. Changing the URL settings can make your site inaccessible from the front or the back end and would require access to the database to recover/repair these settings. With that said, there are cases where you may need to change these settings, such as if you implement SSL and need to change the protocol to https://; just be careful! It might be strange to have two different URL settings, but they have different purposes. The WordPress Codex describes them like this:

*   The "Site Address (URL)" setting is the address you want people to type in their browser to reach your WordPress blog.
*   The "WordPress Address (URL)" setting is the address where your WordPress core files reside.

Most of the time the two URL settings will be the same, but there are times when they maybe different, such as when WordPress is installed in a subdirectory. In that case, the Site Address will include the path. **E-mail Address:** This should be filled out from your WordPress install; however you should check it and/or change it here to reflect the email address to which administrative emails should be sent regarding activity on your site, as well as lost password reset emails. **Membership:** With WordPress, you have the option to allow anyone to register for your site or not. If you select this option, the New User Default Role default is set to subscriber, so that new users have limited access to your WordPress Dashboard. You can change this; however the subscriber level is recommended. You can always change a user's role after they have registered to give them more access/capabilities. **Timezone, Weekday Start, and Language:** Select the city for your preferred timezone and then select your preferred date format. This is the format which will show on the front end of your website when the post meta (author, date, time) is published with new blog posts. Next select which day you want the calendar week to start on. The default is Monday. (WordPress has a calendar widget, which will refer to this setting if you use that widget on your website.)  Finally, select your preferred language from the dropdown list. Once you’ve updated or changed these settings, click **Save changes**.

### Step two: Writing Settings

[![This is a screenshot of the Writing Settings in the Admin Screen in WordPress](https://make.wordpress.org/training/files/2014/12/WordPressWritingSettings.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressWritingSettings.jpg) The Writing Settings refer to blog posts. **Default New Post Settings**: Once you have created some **Post Categories**, select the category here that you want to be the default. If you have not created any categories yet, "Uncategorized" is the default. Whenever you create a new post, this category will automatically be assigned. **Post Formats:** You can change the default format for new posts by choosing a Post Format from this dropdown list. Depending on the theme you have installed, there may be various formats available for your posts. **Post via e-mail** is an advanced feature which usually requires setting up a special email account to which you would send your blog post to be published. This is an optional method, which is much less common and more complicated than creating/posting your blog posts via the Add New Post screen. **Update Services:** This referes to blogrolling services like ping-o-matic, which let other people know you've updated your blog. This allows browsing sites like Technorati or Sphere to find your most recent posts. You must have the Search Engine Visibility setting turned on in Reading Settings (see below) to enable the Update Services setting. Once you’ve updated or change these settings, click **Save Changes**.

### Step three: Reading Settings

[![This is a screenshot of the Reading Settings in the WordPress Dashboard](https://make.wordpress.org/training/files/2014/12/WordPressReadingSettings.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressReadingSettings.jpg) These settings control how posts and pages appear on your site.

**Front Page and Blog Page Options: **WordPress gives you the option of using the default setting for the Home page (front page) of your website, which can show the most recent  blog posts or a static page, or selecting specific pages for the Home page and Blog page of your website. If you would like to set specific pages for these, first create and save these pages then come back to this Settings page to select them from the dropdown menu.

**Blog Post Feed Content Options:** You can limit the number of blog posts which will show on your Blog page, as well as limit the number that will feed into the RSS feed of your blog. The default for each is 10\. You can also specify whether the feed will include a summary or the full content of these posts. This summary is the Post Excerpt metabox on the Create or Edit Post pages, which you can create in the post editor.

**Search Engine Visibility:** If your website is in the development phase, you can choose to check this box to minimize the chances it will be picked up by search engines. When your site goes into production and is ready to be searchable, be sure to uncheck this box.

Once you’ve updated or change these settings, click **Save Changes**.

### Step four: Discussion Settings

[![This is a screenshot of the Discussion Settings in the WordPress Dashboard](https://make.wordpress.org/training/files/2014/12/WordPressDiscussionSettings.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressDiscussionSettings.jpg) The Discussion Settings control commenting and linking on your website. **Default article settings** can be set globally here, as well as individually on each blog post. If you would like to prevent comments on all or most posts, you can set that here, as well as allowing or disallowing trackbacks and pingbacks (when other blogs link to your post). The first setting in this list, which asks if you want WordPress to attempt to notify linked articles/websites when you link to them, is turned off by default. **Other comment settings** determine how WordPress will handle comments when they are posted. These are further defined in [Comments in WordPress](https://codex.wordpress.org/Comments_in_WordPress). **Email me whenever** allows you to be notified when someone posts a comment. If you select the moderation setting in the next option field (**Before a comment appears**), you can select the setting here to be notified when a comment is awaiting your approval. This will use the email address you set on the General Settings page. **Before a comment appears:** If you would like to moderate/approve comments before they appear on your website, select this option. You can also choose to automatically approve comments from those who have previously had approved comments on your website. **Comment Moderation** and **Comment Blacklist** allow you to target specific words, terms and links in comments. When these targeted items are found in a comment you can set the comment to force moderation or to be blacklisted. This can help identify and control spam. **Avatars**: You can select whether or not to show a commenter's avatar when they comment on a post. If you choose to display avatars, you can also control what type of avatar is displayed. Once you’ve updated or change these settings, click **Save Changes**.

### Step five: Media Settings

### [![This is a screenshot of the Media Settings in the WordPress Dashboard](https://make.wordpress.org/training/files/2014/12/WordPressMediaSettings.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressMediaSettings.jpg)

WordPress has default image sizes already set on new websites. You can change these global defaults on this setting screen. You can also choose to use the WordPress image file system, which organizes images into folders based on the month and year when they were uploaded to the site.

Once you’ve updated or change these settings, click **Save Changes**.

### Step six: Permalink Settings

[![This is a screenshot of the Permalink Settings in the WordPress Dashboard](https://make.wordpress.org/training/files/2014/12/WordPressPermalinkSettings.jpg)](https://make.wordpress.org/training/files/2014/12/WordPressPermalinkSettings.jpg) Permalinks determine the URL of each page and post on your website, as well as your category and tag archives. The recommended permalink structure in most cases is the "Post name," sometimes referred to as "Pretty Permalinks."  This can improve the aesthetics, usability, and forward-compatibility of your links, as well as improve the ranking of your site in search engines. Once set, these should not be changed to avoid broken links. You also have the option to set a custom URL structure here. Once you’ve updated or change these settings, click **Save Changes**.

## Exercises

*   Change the timezone of your WordPress website.
*   Set the front page of your website to show as a static page and make your blog page separate. Once this is complete, set the front page back to show your blog.
*   Allow anyone to comment on your blog posts, but require your approval of all comments.
*   Ensure your website is searchable by search engines.
*   Require comments to be manually approved on your website.
*   Set the default thumbnail image size to be 200px x 200px.
*   Set permalinks to use the day and name.

## Quiz

### What setting would you use to have "Pretty Permalinks" on your website?

1.  Custom structure http://example.com/pretty/
2.  Post name
3.  Default

**Answer:** 2\. Post name

### What setting would you use to show an excerpt of your posts on the Blog page, rather than the full content?

1.  Reading Settings > Front page displays your latest posts
2.  General Settings > Site Address URL
3.  Reading Settings > For each article in a feed show > Summary

**Answer:** 3. Reading Settings > For each article in a feed show > Summary

## Additional Resources

[Settings](https://en.support.wordpress.com/settings/) @WordPress Support [Settings General Screen](https://codex.wordpress.org/Settings_General_Screen) @ Codex
