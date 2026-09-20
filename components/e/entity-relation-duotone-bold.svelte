<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zcftkvb4g"/><path class="i_yso9n_l"/><path class="obpp6ab7f"/><path class="ztwbs-b3m"/><path class="bb7inz33j"/><path class="e_3sagvyd"/><path class="wjt99f33m"/><path class="l8l7-n69m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:entity-relation-duotone-bold" {...props}></Icon>
<style>
:global(.bb7inz33j) {
  d: path("M13.5 5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

:global(.e_3sagvyd) {
  d: path("M13.5 16a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

:global(.i_yso9n_l) {
  fill: currentColor;
  d: path("M13.5 5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l8l7-n69m) {
  d: path("M11 12v5.5h2.5");
}

:global(.obpp6ab7f) {
  fill: currentColor;
  d: path("M13.5 16a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
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

:global(.wjt99f33m) {
  d: path("M8.5 12H11V6.5h2.5");
}

:global(.zcftkvb4g) {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ztwbs-b3m) {
  d: path("M2 9a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
