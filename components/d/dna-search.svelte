<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i95qqrb8u"/><path class="pxczfdcfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dna-search" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i95qqrb8u) {
  d: path("M3.5 2.5c0 5 10 5 10 9.5s-10 4.5-10 9.5");
}

:global(.pxczfdcfv) {
  d: path("M13.5 2.5c0 5-10 5-10 9.5c0 3.897 7.5 4.419 9.51 7.737m.141.256c.223.448.349.946.349 1.507M4.5 5h8m-9 7h10m1.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
