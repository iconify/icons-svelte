<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e8jhv79aa"/><path class="f1oz8g1ru"/><path class="tpkkoibhl"/><path class="mu5pjkbqo"/><path class="rnv77s7xr"/><path class="it0a8bbrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chess-duotone-bold" {...props}></Icon>
<style>
:global(.e8jhv79aa) {
  fill: currentColor;
  d: path("M3 3v18h18V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f1oz8g1ru) {
  fill: currentColor;
  d: path("M7 7h3v3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.it0a8bbrp) {
  d: path("M14 14h3v3h-3Z");
}

:global(.mu5pjkbqo) {
  d: path("M3 3v18h18V3Z");
}

:global(.rnv77s7xr) {
  d: path("M7 7h3v3H7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tpkkoibhl) {
  fill: currentColor;
  d: path("M14 14h3v3h-3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
