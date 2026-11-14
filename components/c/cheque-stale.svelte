<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhuvow97a"/><path class="xq7vjccss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-stale" {...props}></Icon>
<style>
:global(.mhuvow97a) {
  d: path("M2.5 5.5h19v13h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xq7vjccss) {
  d: path("M7.5 6.5a4 4 0 0 1-4 4m7-4a7 7 0 0 1-7 7m1-6L9 12M5 7l6 2.5m2 5h5.5m-4-5h4");
}

</style>
