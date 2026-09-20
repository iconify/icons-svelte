<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjia2r6k"/><path class="pj_sixb1z"/><path class="g44ebntoj"/><path class="egcx08b2c"/><path class="tp-jyibgw"/><path class="e7pgrp-wx"/><path class="hcqml3bhu"/><path class="p2i6q-ifg"/><path class="ldxs-ebdf"/><path class="dt_d4knyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:load-balancer-duotone-thin" {...props}></Icon>
<style>
:global(.dt_d4knyh) {
  d: path("M8 18h13");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.egcx08b2c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g44ebntoj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hcqml3bhu) {
  d: path("M8 6v12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldxs-ebdf) {
  d: path("M8 12h13");
}

:global(.p2i6q-ifg) {
  d: path("M8 6h13");
}

:global(.pj_sixb1z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pwjia2r6k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tp-jyibgw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
