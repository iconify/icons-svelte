<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hhg783bmc"/><path class="a_gfszb3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pedestrian-detection" {...props}></Icon>
<style>
:global(.a_gfszb3b) {
  d: path("M9 11.25L11.75 10l2.5 2");
}

:global(.hhg783bmc) {
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m8-8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm.75 2.5L11 13.25L13 15v2.75m-2-4.5L9.75 15.5L8 17.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
