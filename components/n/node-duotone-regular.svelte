<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z705ggbcg"/><path class="dx5s6zbrc"/><path class="e7pgrp-wx"/><path class="p8a31xr4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:node-duotone-regular" {...props}></Icon>
<style>
:global(.dx5s6zbrc) {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p8a31xr4o) {
  d: path("M16 12h6");
}

:global(.z705ggbcg) {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
