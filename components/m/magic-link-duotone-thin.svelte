<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmrvcn97u"/><path class="u5fxe_3rg"/><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="gnu2dod3i"/><path class="cc9vvy32g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magic-link-duotone-thin" {...props}></Icon>
<style>
:global(.a0z9iab1m) {
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
}

:global(.cc9vvy32g) {
  d: path("M10.5 8.5H15");
}

:global(.drjiz3bcf) {
  d: path("M12 21h2.5");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.gnu2dod3i) {
  d: path("M8 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lmrvcn97u) {
  fill: currentColor;
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u5fxe_3rg) {
  fill: currentColor;
  d: path("M8 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xidycypec) {
  d: path("M12 18h3");
}

</style>
