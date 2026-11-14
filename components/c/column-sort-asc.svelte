<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6ii7b98u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:column-sort-asc" {...props}></Icon>
<style>
:global(.j6ii7b98u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h11v18h-11Zm16 18V3.5m-2.75 2.75L18.5 3.5l2.75 2.75M2.5 8h11M8 3v18m-5.5-6.5h11");
}

</style>
