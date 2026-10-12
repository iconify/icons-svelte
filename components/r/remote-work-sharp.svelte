<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gfyvvti5q"/><path class="mux9f8txu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:remote-work-sharp" {...props}></Icon>
<style>
:global(.gfyvvti5q) {
  d: path("M5.25 9.5L12 3.75l6.75 5.75v11.75H5.25v-2Z");
}

:global(.mux9f8txu) {
  d: path("M9 11h6v4.25H9zm-.75 7.25h7.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
