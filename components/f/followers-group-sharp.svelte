<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vwl1wf1bw"/><circle class="l33zoes5a"/><path class="lq_k2klyq"/><circle class="c79v2o9xe"/><path class="w20iw8b0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:followers-group-sharp" {...props}></Icon>
<style>
:global(.c79v2o9xe) {
  cx: 12px;
  cy: 9.5px;
  r: 2.5px;
}

:global(.l33zoes5a) {
  cx: 19px;
  cy: 7px;
  r: 2px;
}

:global(.lq_k2klyq) {
  d: path("m2.75 13.15l2.995-2.857L7.81 13.88m8.38 0l2.065-3.587l2.995 2.857");
}

:global(.vwl1wf1bw) {
  cx: 5px;
  cy: 7px;
  r: 2px;
}

:global(.w20iw8b0m) {
  d: path("M6.5 20.5a5.5 5.5 0 0 1 11 0Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
