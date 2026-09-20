<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crzn5obfu"/><path class="ymp2b4b6u"/><path class="nlzvizopl"/><path class="n4fl2qbbh"/><path class="mg_lwq87g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:patch-window-duotone-bold" {...props}></Icon>
<style>
:global(.crzn5obfu) {
  fill: currentColor;
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mg_lwq87g) {
  d: path("M10.5 11h3");
}

:global(.n4fl2qbbh) {
  d: path("M13.5 8H16v6h-2.5");
}

:global(.nlzvizopl) {
  d: path("M10.5 8H8v6h2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ymp2b4b6u) {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
