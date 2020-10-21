widget = "slider"  # Use the Slider widget
headless = true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = ""  # An HTML color value.
  overlay_img = "background.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.0  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Academic"
  # cta_url = "https://sourcethemes.com/academic/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"
