<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j5js2c39y"/><path class="rfsmvwdbe"/><path class="hfxtr8buy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cash-safe-drop" {...props}></Icon>
<style>
:global(.hfxtr8buy) {
  d: path("M8 11.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm10 3.25v7m-3-3l3 3l3-3");
}

:global(.j5js2c39y) {
  d: path("M12.1 19.5H2.5V3h19v12.1m-16 4.4v2");
}

:global(.rfsmvwdbe) {
  d: path("M13.1 16.5H5.5V6H15v8.6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
