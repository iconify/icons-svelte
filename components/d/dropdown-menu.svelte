<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q9oi50xuy"/><path class="dw08_xb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dropdown-menu" {...props}></Icon>
<style>
:global(.dw08_xb_f) {
  d: path("M15.5 5.5L17 7l1.5-1.5M5 13.5h14M5 18h10");
}

:global(.q9oi50xuy) {
  d: path("M2.5 3h19v6.5h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
