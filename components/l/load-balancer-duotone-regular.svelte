<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqgcmcahi"/><path class="i7lgqsbnp"/><path class="o7hbxg08d"/><path class="lpowjlbtz"/><path class="w1a9p9-xk"/><path class="e7pgrp-wx"/><path class="hcqml3bhu"/><path class="p2i6q-ifg"/><path class="ldxs-ebdf"/><path class="dt_d4knyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:load-balancer-duotone-regular" {...props}></Icon>
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

:global(.i7lgqsbnp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldxs-ebdf) {
  d: path("M8 12h13");
}

:global(.lpowjlbtz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o7hbxg08d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p2i6q-ifg) {
  d: path("M8 6h13");
}

:global(.pqgcmcahi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w1a9p9-xk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
