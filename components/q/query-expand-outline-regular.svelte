<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e7pgrp-wx"/><path class="y5__l6b-e"/><path class="cabegubdh"/><path class="ltxni2ncy"/><path class="gy18-zqeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:query-expand-outline-regular" {...props}></Icon>
<style>
:global(.cabegubdh) {
  d: path("M14 5h7");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.gy18-zqeb) {
  d: path("M14 19h7");
}

:global(.ltxni2ncy) {
  d: path("M14 12h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y5__l6b-e) {
  d: path("m9 10 2.5 2.5L9 15");
}

</style>
