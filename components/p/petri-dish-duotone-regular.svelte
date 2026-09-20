<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wwnijrnro"/><path class="qovnv8ggw"/><path class="wwt33o_li"/><path class="dx4yo_bup"/><path class="ii8ld06oh"/><path class="j835zw5-z"/><path class="lgr612izs"/><path class="a8uaxqbgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:petri-dish-duotone-regular" {...props}></Icon>
<style>
:global(.a8uaxqbgz) {
  d: path("M13 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dx4yo_bup) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ii8ld06oh) {
  d: path("M21 9A9 9 0 0 1 3 9");
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.lgr612izs) {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qovnv8ggw) {
  fill: currentColor;
  d: path("M13 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wwnijrnro) {
  fill: currentColor;
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wwt33o_li) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 9A9 9 0 0 1 3 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
