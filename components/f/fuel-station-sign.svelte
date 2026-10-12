<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="wzoz42r4f"/><path class="k_j-l-bqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fuel-station-sign" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_j-l-bqs) {
  d: path("M8.5 8.5h2.75V11H8.5Z");
}

:global(.wzoz42r4f) {
  d: path("M6 18V7a1 1 0 0 1 1-1h5.75a1 1 0 0 1 1 1v11M5 18h9.75m-1-7.5h1.5a1 1 0 0 1 1 1v4a1.25 1.25 0 0 0 2.5 0V9l-1.5-1.5");
}

</style>
