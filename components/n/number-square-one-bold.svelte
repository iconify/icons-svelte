<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u6wq8bb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-square-one-bold" {...props}></Icon>
<style>
:global(.u6wq8bb2d) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM98 102.66A12 12 0 0 1 101.34 86l24-16A12 12 0 0 1 144 80v96a12 12 0 0 1-24 0v-73.58l-5.34 3.58A12 12 0 0 1 98 102.66");
}

</style>
