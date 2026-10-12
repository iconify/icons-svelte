<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ie50qbcyb"/><path class="lw81labzt"/><path class="pb72_kbtk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:black-hole-sharp" {...props}></Icon>
<style>
:global(.ie50qbcyb) {
  cx: 12px;
  cy: 12px;
  r: 3.25px;
}

:global(.lw81labzt) {
  d: path("M15 6.8A6 6 0 1 1 6.8 15M9 17.2A6 6 0 1 1 17.2 9");
}

:global(.pb72_kbtk) {
  d: path("M20.69 15.16a9.25 9.25 0 0 1-17.38 0m0-6.32a9.25 9.25 0 0 1 17.38 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
