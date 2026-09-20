<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjia2r6k"/><path class="sftcrugme"/><path class="b0batih_b"/><path class="l4pybmb4a"/><path class="ztw87lr4b"/><path class="e7pgrp-wx"/><path class="y5__l6b-e"/><path class="cabegubdh"/><path class="ltxni2ncy"/><path class="gy18-zqeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:query-expand-duotone-thin" {...props}></Icon>
<style>
:global(.b0batih_b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cabegubdh) {
  d: path("M14 5h7");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.gy18-zqeb) {
  d: path("M14 19h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l4pybmb4a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ltxni2ncy) {
  d: path("M14 12h7");
}

:global(.pwjia2r6k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sftcrugme) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 10 2.5 2.5L9 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y5__l6b-e) {
  d: path("m9 10 2.5 2.5L9 15");
}

:global(.ztw87lr4b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
