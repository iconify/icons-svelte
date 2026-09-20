<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtzry4bzy"/><path class="qwp6o_9uk"/><path class="jcyfzkb8f"/><path class="ub37mjw1m"/><path class="f7p-qpb9c"/><path class="rfp-q_b_z"/><path class="lveb61hbp"/><path class="j_t6_obaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-return-duotone-thin" {...props}></Icon>
<style>
:global(.f7p-qpb9c) {
  d: path("m3 12 7 -7 7 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_t6_obaj) {
  d: path("M18.5 13.5 16 16l2.5 2.5");
}

:global(.jcyfzkb8f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lveb61hbp) {
  d: path("M16 16h6");
}

:global(.qwp6o_9uk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12v8h10v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rfp-q_b_z) {
  d: path("M5 12v8h10v-8");
}

:global(.rtzry4bzy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 12 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ub37mjw1m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 13.5 16 16l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
