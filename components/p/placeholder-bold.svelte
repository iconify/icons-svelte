<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i3c3k7b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:placeholder-bold" {...props}></Icon>
<style>
:global(.i3c3k7b8l) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 159L69 52h135ZM52 69l135 135H52Z");
}

</style>
