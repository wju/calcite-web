## Modular Scale

The `modular-scale($n)` behaves the same as the `font-size($n)` mixin, but returns a raw rem value rather than css styles specific to type elements. This means that the `modular-scale($n)` mixin can be used to define heights, widths, padding, margins, or any other property of an element so that it adheres to the modular scale defined by the typography.
Setting the max width of an article to a large multiple of the text size is a way to define a comfortable reading measure related to the proportional decisions of the content.