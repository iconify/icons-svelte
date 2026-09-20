<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gtc-yjbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-square-seven-bold" {...props}></Icon>
<style>
:global(.gtc-yjbrf) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM92 88a12 12 0 0 1 12-12h48a12 12 0 0 1 11.28 16.1l-32 88a12 12 0 0 1-22.56-8.2l26.15-71.9H104a12 12 0 0 1-12-12");
}

</style>
