<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7pgrp-wx"/><path class="hcqml3bhu"/><path class="p2i6q-ifg"/><path class="ldxs-ebdf"/><path class="dt_d4knyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:load-balancer-outline-thin" {...props}></Icon>
<style>
:global(.dt_d4knyh) {
  d: path("M8 18h13");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
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

</style>
