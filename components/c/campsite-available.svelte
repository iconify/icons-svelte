<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dffmec2yo"/><path class="djbhmab0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:campsite-available" {...props}></Icon>
<style>
:global(.dffmec2yo) {
  d: path("M11.778 17H2.5l8-14l7.266 11.967");
}

:global(.djbhmab0x) {
  d: path("m9 17l1.5-4.5l1.441 4.323M2.5 20H10m4.75-2l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
