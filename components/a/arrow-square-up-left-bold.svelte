<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qf9p3_bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-square-up-left-bold" {...props}></Icon>
<style>
:global(.qf9p3_bls) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM84 144V96a12 12 0 0 1 12-12h48a12 12 0 0 1 0 24h-19l43.52 43.51a12 12 0 0 1-17 17L108 125v19a12 12 0 0 1-24 0");
}

</style>
