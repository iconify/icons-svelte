<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e7pgrp-wx"/><path class="zmj1nccll"/><path class="zcbyubc5i"/><path class="p8a31xr4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:private-link-outline-bold" {...props}></Icon>
<style>
:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.p8a31xr4o) {
  d: path("M16 12h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zcbyubc5i) {
  d: path("M9.5 8.5a2.5 2.5 0 0 1 5 0");
}

:global(.zmj1nccll) {
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
