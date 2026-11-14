<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l227mbcus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bench-armrests" {...props}></Icon>
<style>
:global(.l227mbcus) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19v3.5h-19Zm3 3.5l-1 6m14-6l1 6M3.75 10V5.5H8.5M20.25 10V5.5H15.5");
}

</style>
