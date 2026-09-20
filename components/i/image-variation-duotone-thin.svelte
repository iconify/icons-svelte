<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v1yds1b4t"/><path class="gd8ypzfbh"/><path class="mn0_wbcmu"/><path class="d9acmebfe"/><path class="x6s5o0ble"/><path class="ulvbol07x"/><path class="uberx3r9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:image-variation-duotone-thin" {...props}></Icon>
<style>
:global(.d9acmebfe) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.gd8ypzfbh) {
  fill: currentColor;
  d: path("M8 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mn0_wbcmu) {
  fill: currentColor;
  d: path("M14 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uberx3r9c) {
  d: path("M14 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ulvbol07x) {
  d: path("M8 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.v1yds1b4t) {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x6s5o0ble) {
  d: path("m6 11 4 -4 3 3 4 -4");
}

</style>
