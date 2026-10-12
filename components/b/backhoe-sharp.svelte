<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dg0no4l4v"/><circle class="o48oad76n"/><circle class="yryo9i7wh"/><path class="houlg8gce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:backhoe-sharp" {...props}></Icon>
<style>
:global(.dg0no4l4v) {
  d: path("M11 11h4V5h3.5l.909-.005l.091.905l.5 5.1h1.25v3H10v-3z");
}

:global(.houlg8gce) {
  d: path("M10.75 11L6 3.25l-2.25 11.5m3.25 0H2.75v6h5.5L7.5 18.5");
}

:global(.o48oad76n) {
  cx: 13px;
  cy: 18.75px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yryo9i7wh) {
  cx: 19.5px;
  cy: 18.75px;
  r: 1.75px;
}

</style>
