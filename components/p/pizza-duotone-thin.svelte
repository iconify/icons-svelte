<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apjaaebsc"/><path class="zi7f37b4e"/><path class="i9yv2ebba"/><path class="bifuny-1t"/><path class="n1soxcq3c"/><path class="vzyxlnb8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pizza-duotone-thin" {...props}></Icon>
<style>
:global(.apjaaebsc) {
  fill: currentColor;
  d: path("M12 18 2 8h20Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bifuny-1t) {
  d: path("M12 18 2 8h20Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9yv2ebba) {
  fill: currentColor;
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n1soxcq3c) {
  d: path("M8 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vzyxlnb8e) {
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zi7f37b4e) {
  fill: currentColor;
  d: path("M8 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
