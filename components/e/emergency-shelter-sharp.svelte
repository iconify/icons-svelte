<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eknilkb-t"/><path class="k08upyb9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:emergency-shelter-sharp" {...props}></Icon>
<style>
:global(.eknilkb-t) {
  d: path("m12.6 4.59l8.05 14.57l.6 1.09H2.75l.6-1.09L11.4 4.59L12 3.5z");
}

:global(.k08upyb9l) {
  d: path("m12 11.5l3.5 8.75h-7Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
