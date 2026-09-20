<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gkidedb4h"/><path class="dktry7bqc"/><path class="sjwck004e"/><path class="bo51iypxr"/><path class="uw8-z-bjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recital-duotone-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gkidedb4h) {
  fill: currentColor;
  d: path("M10.5 2 6 6.5h11.5L13 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sjwck004e) {
  d: path("M10.5 2 6 6.5h11.5L13 2Z");
}

:global(.uw8-z-bjv) {
  d: path("M7 20a5 5 0 0 1 10 0");
}

</style>
