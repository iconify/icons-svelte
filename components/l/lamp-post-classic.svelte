<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7xcpitsy"/><path class="xo0e832cs"/><path class="v65aobfkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lamp-post-classic" {...props}></Icon>
<style>
:global(.c7xcpitsy) {
  d: path("M8 19V6.5a4 4 0 0 1 4-4h4V5M5.5 21.5l1-2.5h3l1 2.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v65aobfkd) {
  d: path("M15.521 7.5h.958a1.5 1.5 0 0 1 1.48 1.747l-.504 3.02A1.476 1.476 0 0 1 16 13.5a1.476 1.476 0 0 1-1.455-1.233l-.504-3.02a1.5 1.5 0 0 1 1.48-1.747");
}

:global(.xo0e832cs) {
  d: path("m16 5l2.75 2.5h-5.5Z");
}

</style>
