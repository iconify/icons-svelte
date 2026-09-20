<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="szcoycbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-double-right-16-filled" {...props}></Icon>
<style>
:global(.szcoycbjs) {
  fill: currentColor;
  d: path("M3.47 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.75.75 0 0 1-1.06-1.06L7.19 8L3.47 4.28a.75.75 0 0 1 0-1.06m4.5 0a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.75.75 0 0 1-1.06-1.06L11.69 8L7.97 4.28a.75.75 0 0 1 0-1.06");
}

</style>
