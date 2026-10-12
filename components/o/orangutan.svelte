<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j1w_oobwv"/><path class="daxgvdb-d"/><path class="fl8ls8bxt"/><path class="zt4l6v3fu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:orangutan" {...props}></Icon>
<style>
:global(.daxgvdb-d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 10c0-1.5 1.5-2.75 3.75-2.75S15.75 8.5 15.75 10v3.5C15.75 16.25 14 18 12 18s-3.75-1.75-3.75-4.5ZM4.5 16L4 18.5M19.5 16l.5 2.5");
}

:global(.fl8ls8bxt) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 10.75h.01m2.99 0h.01");
}

:global(.j1w_oobwv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c3 0 5 1.75 5.25 4.5l2.5.5c1 .25 1.5 1.25 1.5 2.75v2c0 1.5-.5 2.5-1.75 2.75l-2 .25C17.25 19 15 21 12 21s-5.25-2-5.5-4.75l-2-.25c-1.25-.25-1.75-1.25-1.75-2.75v-2c0-1.5.5-2.5 1.5-2.75l2.5-.5C7 5.25 9 3.5 12 3.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zt4l6v3fu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 15.25q1.5.9 3 0");
}

</style>
