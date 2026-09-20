<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_k2t6-nh"/><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="xeo8ox-td"/><path class="ey7vq22fn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:report-user-duotone-thin" {...props}></Icon>
<style>
:global(.ey7vq22fn) {
  d: path("m16 5 5 5h-5");
}

:global(.f69zonn4h) {
  d: path("M4 17a4 4 0 0 1 8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_k2t6-nh) {
  fill: currentColor;
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q8-0ejn0y) {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.xeo8ox-td) {
  d: path("M16 5v15");
}

</style>
