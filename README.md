Day1:
    1. CSS Priority:
      inline style > id > attribute > class > element

    2. margin border padding
      margin: is the space around an element's border.
      padding: is the space between an element's border and the element's content.

      By other way:
        the margin property controls the space outside an element,
        and the padding property controls the space inside and element.

    3. Three CSS style method
        inline > internal > external
        inline only care about the particular element.
        internal only care about one web page.
        external can be used for multiple web pages.

        3.1 inline: e.g., <h1 style="color: red">This is red text</h1>
        3.2 internal: e.g., often position in the <head></head> part
            <head>
                <style type="text/css">
                    h1 {
                        color: red;
                    }
                </style>
            </head>
        3.3 external: e.g., it is a individual file, should import in the root file
            in root file(html file), it should be 
            <link rel="stylesheet" href="filename.css">
            in the <head> part

    4. see 7.1file
        4.1 c=Child = Apply to direct child of left side
        selector > selector {
            color: red;
        }
        .box > .done {
            color: firebrick;
        }

        4.2 Descendant = Apply to a descendent of left side
        selector selector {
            color: blue;
        }

        4.3 Chaining = Apply where all selectors are true
        selectorselector {
            color: seagreen;
        }
        li.done {
            color: seagreen;
        }

        4.4 Combining Combiners
        selector selectorselector {
            font-size: 2rem;
        }

Day2
    1. Position: Static Relative Absolute Z-index Fixed 
        Static: HTML default flow

        Relative: Position relative to default position

        Absolute: Position relative to nearest positioned ancestor or top left corner of webpage

        Fixed: Position relative to top left corner of browser window

Day3
    1. Display Property
        block inline inline-block


Day4 Flex Layout
    1. order
    2. flex-wrap 

Day4 flex sizing
    content width < width < flex-basis < min-width/max-width

Day5 project summary
    1. height: 100vh VS height: 100%
        100vh基于视口高度，而100%基于其父元素的高度
        
    2. flex: 1
        flex-shrink:1 flex-grow:1 flex-basis:0%(equal)

    
