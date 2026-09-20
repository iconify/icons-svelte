<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukep6hbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-circle-20-filled" {...props}></Icon>
<style>
:global(.ukep6hbpx) {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-3 8a1 1 0 1 1-2 0a1 1 0 0 1 2 0m4 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0m4 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
