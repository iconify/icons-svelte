<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1y0pt0wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:airplane-landing" {...props}></Icon>
<style>
:global(.t1y0pt0wa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20h18M3.5 8L8 9l5-2l6 2.5c2 1 1.5 3-.5 3l-6.5-1L6.5 14L5 12.5l3.5-2");
}

</style>
