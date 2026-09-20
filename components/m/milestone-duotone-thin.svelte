<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ior14cbcm"/><path class="qshaw154e"/><path class="afx93-brk"/><path class="z9ittvbis"/><path class="vavi9cbgb"/><path class="k5g5kukae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:milestone-duotone-thin" {...props}></Icon>
<style>
:global(.afx93-brk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 7h10l-4 4 4 4H8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k5g5kukae) {
  d: path("M8 7h10l-4 4 4 4H8");
}

:global(.qshaw154e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vavi9cbgb) {
  d: path("M8 7v12");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
