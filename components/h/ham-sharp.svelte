<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r05tk7brq"/><circle class="u2y4_zbrn"/><circle class="k__z_1b2n"/><path class="ps32ppjfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ham-sharp" {...props}></Icon>
<style>
:global(.k__z_1b2n) {
  cx: 6.75px;
  cy: 4.5px;
  r: 1.5px;
}

:global(.ps32ppjfb) {
  d: path("M17.6 13.5a3 3 0 0 1-4.1 4.1");
}

:global(.r05tk7brq) {
  d: path("m9.75 7.75l2 1.25l2.25.1A6 6 0 1 1 9.1 14L9 11.75l-1.25-2Zm-1 1L6 6");
}

:global(.u2y4_zbrn) {
  cx: 4.5px;
  cy: 6.75px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
