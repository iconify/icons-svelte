<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w9_o54bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rewind-16-filled" {...props}></Icon>
<style>
:global(.w9_o54bsb) {
  fill: currentColor;
  d: path("M8 4.465a1 1 0 0 0-1.576-.818L1.412 7.183a1 1 0 0 0 0 1.634l5.012 3.536A1 1 0 0 0 8 11.536V9.232l4.424 3.12A1 1 0 0 0 14 11.537V4.465a1 1 0 0 0-1.576-.818L8 6.768z");
}

</style>
