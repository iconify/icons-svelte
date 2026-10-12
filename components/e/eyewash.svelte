<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="dy0wr_biw"/><path class="m9me6bb5j"/><path class="q_7nk9trv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eyewash" {...props}></Icon>
<style>
:global(.aqmj_4big) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.dy0wr_biw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.5q2.625-3 6-3c3.375 0 4.25 1 6 3q-2.625 3-6 3c-3.375 0-4.25-1-6-3");
}

:global(.m9me6bb5j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

:global(.q_7nk9trv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 17.75C9.5 16 10 15 11 14m3.5 3.75C14.5 16 14 15 13 14m-5.5 4h9");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
