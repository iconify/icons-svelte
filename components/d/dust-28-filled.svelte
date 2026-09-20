<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="wm896b9zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dust-28-filled" {...props}></Icon>
<style>
:global(.wm896b9zg) {
  fill: currentColor;
  d: path("M10.242 7.736A6.5 6.5 0 1 1 21.19 14a6.5 6.5 0 1 1-10.948 6.264a6.5 6.5 0 1 1 0-12.527M8 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m18 9a1 1 0 1 1-2 0a1 1 0 0 1 2 0M9 24a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
