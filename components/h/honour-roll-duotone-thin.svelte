<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttrxo2bov"/><path class="jqxl7db2x"/><path class="tu0fdo1xi"/><path class="uepsd3bvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:honour-roll-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jqxl7db2x) {
  d: path("M4 3h16v17l-8 -8 -8 8Z");
}

:global(.ttrxo2bov) {
  fill: currentColor;
  d: path("M4 3h16v17l-8 -8 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tu0fdo1xi) {
  d: path("M7 7h10");
}

:global(.uepsd3bvn) {
  d: path("M7 10h7");
}

</style>
