<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="dtzxwi1sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-left-28-filled" {...props}></Icon>
<style>
:global(.dtzxwi1sk) {
  fill: currentColor;
  d: path("M24.707 3.293a1 1 0 0 1 0 1.414L6.414 23H15a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1V13a1 1 0 1 1 2 0v8.586L23.293 3.293a1 1 0 0 1 1.414 0");
}

</style>
