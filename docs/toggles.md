---
hide:
  - toc
---

# Toggles
## Class
=== "Selected No Icon"
    <div class="btn-grid-1" data-theme>
        <div class="grid-items"> 
            <label class='toggle -selected'>
                <input type='checkbox' class="check" checked>
                <span class='slider'>
                </span>
            </label>
        </div>
    </div>
    <br>
    ## States
    === "Default"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle -selected'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Hover"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle -selected hover'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Focused"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle -selected focus'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Pressed"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle -selected pressed'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Disabled"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle -selected disabled'>
                    <input type='checkbox' class="check" checked disabled>
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    <br>
    ## Code
    === "CSS"
        ``` css
        --8<-- "components/sass/components/_toggle.scss:toggle"
        ```
    === "HTML"
        ``` html
        <label class='toggle -selected'>
            <input type='checkbox' class="check" checked>
            <span class='slider'></span>
        </label>
        ```

=== "Selected w/ Icon"
    <div class="btn-grid-1" data-theme>
        <div class="grid-items"> 
            <label class='toggle-icon -selected'>
                <input type='checkbox' class="check" checked>
                <span class='slider'>
                    :material-check:{.icon .-checked}
                    :octicons-x-16:{.icon .-unchecked}
                </span>
            </label>
        </div>
    </div>
    <br>
    ## States
    === "Default"
        <div class="btn-grid-1">
            <div class="grid-items"> 
                <label class='toggle-icon -selected'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'>
                      :material-check:{.icon .-checked}
                      :octicons-x-16:{.icon .-unchecked}
                    </span>
                </label>
            </div>
        </div>
    === "Hover"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon -selected hover'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'>
                      :material-check:{.icon .-checked}
                      :octicons-x-16:{.icon .-unchecked}
                    </span>
                </label>
            </div>
        </div>
    === "Focused"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon -selected focus'>
                    <input type='checkbox' class="check"checked>
                    <span class='slider'>
                        :material-check:{.icon .-checked}
                        :octicons-x-16:{.icon .-unchecked}
                    </span>                
                </label>
            </div>
        </div>
    === "Pressed"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon -selected pressed'>
                    <input type='checkbox' class="check" checked>
                    <span class='slider'>
                        :material-check:{.icon .-checked}
                        :octicons-x-16:{.icon .-unchecked}
                    </span>   
                </label>
            </div>
        </div>
    === "Disabled"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon -selected disabled' >
                    <input type='checkbox' class="check" checked disabled>
                    <span class='slider'>
                        :material-check:{.icon .-checked}
                        :octicons-x-16:{.icon .-unchecked}
                    </span>   
                </label>
            </div>
        </div>
    <br>
    ## Code
    === "CSS" 
        ``` css
        --8<-- "components/sass/components/_toggle.scss:toggle-icon-selected"
        ```
    === "HTML"
        ``` html  
        <label class='toggle-icon -selected' >
            <input type='checkbox' class="check" checked>
            <span class='slider'>
                :material-check:{.icon .-checked}
                :octicons-x-16:{.icon .-unchecked}
            </span>
        </label>
        ```

=== "De-Selected No Icon"
    <div class="btn-grid-1" data-theme>
        <div class="grid-items"> 
            <label class='toggle' >
                <input type='checkbox' class="check">
                <span class='slider'>
                </span>
            </label>
        </div>
    </div>
    <br>
    ## States
    === "Default"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle' >
                    <input type='checkbox' class="check">
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Hover"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle hover' >
                    <input type='checkbox' class="check">
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Focused"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle focus'>
                    <input type='checkbox' class="check">
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Pressed"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle pressed'>
                    <input type='checkbox' class="check">
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    === "Disabled"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle disabled'>
                    <input type='checkbox' class="check" disabled>
                    <span class='slider'></span>
                </label>
            </div>
        </div>
    <br>
    ## Code
    === "CSS"
        ``` css
        --8<-- "components/sass/components/_toggle.scss:toggle"
        ```
    === "HTML"
      ``` html
      <label class='toggle'>
          <input type='checkbox' class="check">
          <span class='slider'></span>
      </label>
      ```

=== "De-Selected w/ Icon"
    <div class="btn-grid-1" data-theme>
        <div class="grid-items"> 
            <label class='toggle-icon' >
                <input type='checkbox' class="check">
                <span class='slider'>
                    :material-check:{.icon .-checked}
                    :octicons-x-16:{.icon .-unchecked}
                </span>
            </label>
        </div>
    </div>
    <br>
    ## States
    === "Default"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon'>
                    <input type='checkbox' class="check">
                    <span class='slider'>
                      :material-check:{.icon .-checked}
                      :octicons-x-16:{.icon .-unchecked}
                    </span>
                </label>
            </div>
        </div>
    === "Hover"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon hover' >
                    <input type='checkbox' class="check">
                    <span class='slider'>
                      :material-check:{.icon .-checked}
                      :octicons-x-16:{.icon .-unchecked}
                    </span>
                </label>
            </div>
        </div>
    === "Focused"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon focus'>
                    <input type='checkbox' class="check">
                    <span class='slider'>
                        :material-check:{.icon .-checked}
                        :octicons-x-16:{.icon .-unchecked}
                    </span>                
                </label>
            </div>
        </div>
    === "Pressed"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon pressed'>
                    <input type='checkbox' class="check">
                    <span class='slider'>
                        :material-check:{.icon .-checked}
                        :octicons-x-16:{.icon .-unchecked}
                    </span>   
                </label>
            </div>
        </div>
    === "Disabled"
        <div class="btn-grid-1" data-theme>
            <div class="grid-items"> 
                <label class='toggle-icon disabled'>
                    <input type='checkbox' class="check" disabled>
                    <span class='slider'>
                        :material-check:{.icon .-checked}
                        :octicons-x-16:{.icon .-unchecked}
                    </span>   
                </label>
            </div>
        </div>
    <br>
    ## Code
    === "CSS"
        ``` css
        --8<-- "components/sass/components/_toggle.scss:toggle-icon"
        ```
    === "HTML"
        ``` html
        <label class='toggle-icon' >
            <input type='checkbox' class="check">
            <span class='slider'>
                :material-check:{.icon .-checked}
                :octicons-x-16:{.icon .-unchecked}
            </span>
        </label>
        ```