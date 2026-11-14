<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vxxn6ybuj"/><path class="hff_2qbds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:oven" {...props}></Icon>
<style>
:global(.hff_2qbds) {
  d: path("M6.5 11h11v7h-11Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vxxn6ybuj) {
  d: path("M3 3h18v18H3Zm10.5 4h.01M17 7h.01");
}

</style>
