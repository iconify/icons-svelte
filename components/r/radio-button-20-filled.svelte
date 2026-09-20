<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u8c_bfm9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:radio-button-20-filled" {...props}></Icon>
<style>
:global(.u8c_bfm9e) {
  fill: currentColor;
  d: path("M10 15a5 5 0 1 0 0-10a5 5 0 0 0 0 10m0-13a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-7 8a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
