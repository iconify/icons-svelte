<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m9__qepra"/><path class="zxdhbfg8h"/><circle class="dg7n60pmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bracelet-sharp" {...props}></Icon>
<style>
:global(.dg7n60pmh) {
  cx: 12px;
  cy: 18.5px;
  r: 1.75px;
}

:global(.m9__qepra) {
  d: path("M2.75 8.75a9.25 5 0 1 0 18.5 0a9.25 5 0 1 0-18.5 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxdhbfg8h) {
  d: path("M2.75 8.75v3a9.25 5 0 0 0 18.5 0v-3");
}

</style>
