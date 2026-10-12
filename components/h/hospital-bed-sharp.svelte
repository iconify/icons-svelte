<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gplilobog"/><circle class="akzn_2afg"/><path class="h4-4wibbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hospital-bed-sharp" {...props}></Icon>
<style>
:global(.akzn_2afg) {
  cx: 7.25px;
  cy: 11.5px;
  r: 2px;
}

:global(.gplilobog) {
  d: path("M2.75 5.5v14.75m0-4.25h18v4.25");
}

:global(.h4-4wibbe) {
  d: path("M11.75 16v-5.75h9V16M16 3.75v4.5M13.75 6h4.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
