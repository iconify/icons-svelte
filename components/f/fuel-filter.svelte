<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w2hnhqb_f"/><path class="x_f0e_b8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fuel-filter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w2hnhqb_f) {
  width: 13.5px;
  height: 11.5px;
  x: 5.25px;
  y: 6.25px;
  rx: 3px;
}

:global(.x_f0e_b8e) {
  d: path("M2.75 12h2.5m13.5 0h2.5M12 8.5c-1.5 1.75-2.75 3.25-2.75 4.75a2.75 2.75 0 0 0 5.5 0c0-1.5-1.25-3-2.75-4.75");
}

</style>
