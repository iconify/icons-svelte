<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="e073lll3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bookmark-simple-thin" {...props}></Icon>
<style>
:global(.e073lll3d) {
  fill: currentColor;
  d: path("M184 36H72a12 12 0 0 0-12 12v176a4 4 0 0 0 6.12 3.39L128 188.72l61.89 38.67a4 4 0 0 0 2.11.61a4.06 4.06 0 0 0 1.94-.5A4 4 0 0 0 196 224V48a12 12 0 0 0-12-12m4 180.78l-57.89-36.17a4 4 0 0 0-4.24 0L68 216.78V48a4 4 0 0 1 4-4h112a4 4 0 0 1 4 4Z");
}

</style>
