<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h2d8t63yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:minus-square-bold" {...props}></Icon>
<style>
:global(.h2d8t63yb) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM76 128a12 12 0 0 1 12-12h80a12 12 0 0 1 0 24H88a12 12 0 0 1-12-12");
}

</style>
