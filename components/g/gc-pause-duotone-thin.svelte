<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjia2r6k"/><path class="x5zrl2b2s"/><path class="gs1vh8b3k"/><path class="gfk0lbm8g"/><path class="e7pgrp-wx"/><path class="wp75hkmty"/><path class="rutulxlvn"/><path class="e69i7fcek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gc-pause-duotone-thin" {...props}></Icon>
<style>
:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.gfk0lbm8g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gs1vh8b3k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pwjia2r6k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rutulxlvn) {
  d: path("M14 7v10");
}

:global(.wp75hkmty) {
  d: path("M11 7v10");
}

:global(.x5zrl2b2s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
