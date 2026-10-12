<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ryq_8nn6w"/><path class="h152-nnyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:import-media-sharp" {...props}></Icon>
<style>
:global(.h152-nnyd) {
  d: path("M13.75 2.75v5.5h5.5M2.75 14.5h10m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

:global(.ryq_8nn6w) {
  d: path("M4.75 11.25v-8.5h9l5.5 5.5v13H4.75v-3.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
