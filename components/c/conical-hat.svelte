<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0zb51t1k"/><path class="n8l86rbdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:conical-hat" {...props}></Icon>
<style>
:global(.i0zb51t1k) {
  d: path("m3 14.5l9-10l9 10q-9 2.5-18 0Z");
}

:global(.n8l86rbdw) {
  d: path("M7.25 15.5q4.75 6.5 9.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
