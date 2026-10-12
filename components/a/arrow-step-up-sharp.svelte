<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bcigp9a4c"/><path class="z9g08dbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-step-up-sharp" {...props}></Icon>
<style>
:global(.bcigp9a4c) {
  d: path("M3.75 20.25h5v-5h5v-5h3.5V4.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z9g08dbag) {
  d: path("m14.25 7.5l3-3l3 3");
}

</style>
