<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaiwdvo8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cart-total" {...props}></Icon>
<style>
:global(.zaiwdvo8m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14V21l-2.5-1.75L14 21l-2.5-1.75L9 21l-1.5-1L5 21ZM8.5 6h7m-7 3H13m-4.5 3.5h7m-7 3.25h7");
}

</style>
