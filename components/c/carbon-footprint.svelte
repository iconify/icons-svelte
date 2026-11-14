<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8vthbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carbon-footprint" {...props}></Icon>
<style>
:global(.nv8vthbrg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.5a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Zm-3.5 6h17m-14 0V18H10v3.5");
}

</style>
