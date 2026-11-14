<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="netaoinie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cart-total" {...props}></Icon>
<style>
:global(.netaoinie) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14V21l-2.5-1.75L14 21l-2.5-1.75L9 21l-1.5-1L5 21ZM8.5 6h7m-7 3H13m-4.5 3.5h7m-7 3.25h7");
}

</style>
