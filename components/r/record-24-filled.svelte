<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-j1hcc8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-24-filled" {...props}></Icon>
<style>
:global(.a-j1hcc8m) {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m10 6a6 6 0 1 0 0-12a6 6 0 0 0 0 12");
}

</style>
