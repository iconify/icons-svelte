<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hjy8rqkzo"/><path class="j6v5-qbsu"/><path class="wvg4ydbao"/><path class="kj-obfgou"/><path class="yc921jgtb"/><path class="naeroc6tm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compute-duotone-thin" {...props}></Icon>
<style>
:global(.hjy8rqkzo) {
  fill: currentColor;
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6v5-qbsu) {
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.kj-obfgou) {
  d: path("M9 22h6");
}

:global(.naeroc6tm) {
  d: path("M22 9v6");
}

:global(.wvg4ydbao) {
  d: path("M9 2h6");
}

:global(.yc921jgtb) {
  d: path("M2 9v6");
}

</style>
