## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/yoeka821/github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
{
    title: {
        text: "2014-2018国内综合餐饮店营业额",
        subtext: "",
        textStyle: {
            fontSize: 13
        }
    },
    tooltip: {
        trigger: "axis"
    },
    legend: {
        data: ["单位（万）"]
    },
    toolbox: {
        show: true,
        feature: {
            mark: {
                show: true
            },
            dataView: {
                show: true,
                readOnly: true
            },
            magicType: {
                show: false,
                type: ["line", "bar"]
            },
            restore: {
                show: true
            },
            saveAsImage: {
                show: true
            }
        }
    },
    calculable: true,
    xAxis: [
        {
            type: "category",
            boundaryGap: false,
            data: ["16Q3", "16Q4", "17Q1", "17Q2", "17Q3", "17Q4", "18Q1", "18Q2", "18Q3"]
        }
    ],
    yAxis: [
        {
            type: "value",
            name: "°C"
        }
    ],
    series: [
        {
            type: "line",
            name: "单位（万）",
            data: [19, 19, 19, 21, 23, 25, 27, 34, 41]
        }
    ]
}

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yoeka821/github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
