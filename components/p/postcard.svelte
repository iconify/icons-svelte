<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="fs6q0ub2y"/><rect class="j7am3v5fe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:postcard" {...props}></Icon>
<style>
:global(.fs6q0ub2y) {
  d: path("M12 8.5v7M5.75 10h3.5m-3.5 3h3.5m5.25 2.5h3.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7am3v5fe) {
  width: 3.25px;
  height: 3.75px;
  x: 15px;
  y: 8px;
  rx: 0.75px;
}

:global(.q0_gb6qzx) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

</style>
