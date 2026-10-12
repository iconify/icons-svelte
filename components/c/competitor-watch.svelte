<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="x_v1iebfy"/><path class="x10pqqb5f"/><circle class="qfz3y5phf"/><path class="oeertebhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:competitor-watch" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oeertebhf) {
  d: path("M15.5 21.25h5a.75.75 0 0 0 .75-.75c0-2.6-1.5-4.5-3.25-4.5s-3.25 1.9-3.25 4.5a.75.75 0 0 0 .75.75m-2.25-17.5l-2.5 5h2.5l-2.5 5");
}

:global(.qfz3y5phf) {
  cx: 18px;
  cy: 10.25px;
  r: 2.25px;
}

:global(.x_v1iebfy) {
  cx: 6px;
  cy: 10.25px;
  r: 2.25px;
}

:global(.x10pqqb5f) {
  d: path("M3.5 21.25h5a.75.75 0 0 0 .75-.75c0-2.6-1.5-4.5-3.25-4.5s-3.25 1.9-3.25 4.5a.75.75 0 0 0 .75.75");
}

</style>
