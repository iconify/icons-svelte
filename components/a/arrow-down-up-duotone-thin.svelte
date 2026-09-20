<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k86txfbxx"/><path class="etn3ob7cq"/><path class="r4q7pxbjl"/><path class="q9sro5bfh"/><path class="gg9qhlhxo"/><path class="v5g-gqbwm"/><path class="pa1ot6bmg"/><path class="wm_1lkfim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-up-duotone-thin" {...props}></Icon>
<style>
:global(.etn3ob7cq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gg9qhlhxo) {
  d: path("M8 4v16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k86txfbxx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pa1ot6bmg) {
  d: path("M16 4v16");
}

:global(.q9sro5bfh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r4q7pxbjl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v5g-gqbwm) {
  d: path("m4 16 4 4 4 -4");
}

:global(.wm_1lkfim) {
  d: path("m12 8 4 -4 4 4");
}

</style>
