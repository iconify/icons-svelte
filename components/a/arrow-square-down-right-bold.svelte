<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nh40j4b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-square-down-right-bold" {...props}></Icon>
<style>
:global(.nh40j4b5p) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM87.51 104.49a12 12 0 0 1 17-17L148 131v-19a12 12 0 0 1 24 0v48a12 12 0 0 1-12 12h-48a12 12 0 0 1 0-24h19Z");
}

</style>
