<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hyu6tnq8g"/><circle class="upu83lbfh"/><path class="lj9r6l14u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:minutes" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hyu6tnq8g) {
  d: path("M9.75 21.25h-3.5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v5M7.5 7H14m-6.5 3.5H14M7.5 14h3");
}

:global(.lj9r6l14u) {
  d: path("M17 15v2l1.25.75");
}

:global(.upu83lbfh) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

</style>
