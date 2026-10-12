<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xj83ecbdh"/><path class="bhg2ekjvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-arc-up-sharp" {...props}></Icon>
<style>
:global(.bhg2ekjvz) {
  d: path("m13 8.75l4-4l4 4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xj83ecbdh) {
  d: path("M3.75 19.25c8 0 13.25-4.75 13.25-14.5");
}

</style>
