<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="erio2v7qq"/><rect class="uncvak0dc"/><path class="gfq8zhbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:metric-up" {...props}></Icon>
<style>
:global(.erio2v7qq) {
  width: 4px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 1px;
}

:global(.gfq8zhbzg) {
  d: path("M18 21.25V4.5m-3.25 3L18 4.25l3.25 3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uncvak0dc) {
  width: 4px;
  height: 12px;
  x: 9px;
  y: 9.25px;
  rx: 1px;
}

</style>
