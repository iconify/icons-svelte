<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw0x1wbxg"/><path class="x8_s66bwx"/><path class="zanislbzu"/><path class="mcubrkb2y"/><path class="c4khiwgvb"/><path class="iq7hdacem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:direct-debit-duotone-thin" {...props}></Icon>
<style>
:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iq7hdacem) {
  d: path("M10.5 12.5 8 15l2.5 2.5");
}

:global(.mcubrkb2y) {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

:global(.x8_s66bwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yw0x1wbxg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zanislbzu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12.5 8 15l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
