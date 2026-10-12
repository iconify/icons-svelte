<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ofqqfjbuw"/><rect class="mnlg2gbmj"/><rect class="zn8ibpofd"/><path class="o43yxpb3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-flat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mnlg2gbmj) {
  width: 3.5px;
  height: 6px;
  x: 10.25px;
  y: 14.25px;
  rx: 1px;
}

:global(.o43yxpb3h) {
  d: path("M2.75 8.75h17.5M17 5.5l3.25 3.25L17 12");
}

:global(.ofqqfjbuw) {
  width: 3.5px;
  height: 6px;
  x: 3.75px;
  y: 14.25px;
  rx: 1px;
}

:global(.zn8ibpofd) {
  width: 3.5px;
  height: 6px;
  x: 16.75px;
  y: 14.25px;
  rx: 1px;
}

</style>
