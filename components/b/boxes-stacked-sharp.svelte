<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v65jr_b0s"/><path class="aau43sk9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boxes-stacked-sharp" {...props}></Icon>
<style>
:global(.aau43sk9w) {
  d: path("M10 4.75h4v6.75h-4zm4.5 12.5H18");
}

:global(.v65jr_b0s) {
  d: path("M2.75 4.75h18.5v16.5H2.75zm0 4.5h18.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
