<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mrog_7b0y"/><path class="jsg8mwb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gift-card-sharp" {...props}></Icon>
<style>
:global(.jsg8mwb7y) {
  d: path("M8.75 11c-1-2.25-3-2.25-3 0s2 2.25 3 0Zm0 0c1-2.25 3-2.25 3 0s-2 2.25-3 0Z");
}

:global(.mrog_7b0y) {
  d: path("M2.75 5.75h18.5v12.5H2.75zm0 5.25h3m6 0h9.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
