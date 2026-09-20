<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n95mv7bdf"/><path class="wwnijrnro"/><path class="sdgafkcgw"/><path class="lgr612izs"/><path class="aagj9lb5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goal-met-duotone-regular" {...props}></Icon>
<style>
:global(.aagj9lb5p) {
  d: path("m17 13 2 2 3 -3");
}

:global(.lgr612izs) {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n95mv7bdf) {
  fill: currentColor;
  d: path("M4 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sdgafkcgw) {
  d: path("M4 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.wwnijrnro) {
  fill: currentColor;
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
