<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sv5la6biz"/><path class="cu26jmb_i"/><path class="x50q_4bdr"/><path class="qaa4bo00g"/><path class="j6apg33fy"/><path class="gx5t5bbfu"/><path class="r6b2dcc9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:free-cancellation-duotone-thin" {...props}></Icon>
<style>
:global(.cu26jmb_i) {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.gx5t5bbfu) {
  d: path("m7 13 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6apg33fy) {
  d: path("M16 2.5V5");
}

:global(.qaa4bo00g) {
  d: path("M8 2.5V5");
}

:global(.r6b2dcc9e) {
  d: path("m11 13 -4 4");
}

:global(.sv5la6biz) {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
