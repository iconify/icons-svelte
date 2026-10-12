<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x7dub9b0d"/><path class="s-_5zua6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:apartment-search-sharp" {...props}></Icon>
<style>
:global(.s-_5zua6t) {
  d: path("M10.5 21.25v-3.5h3v3.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x7dub9b0d) {
  d: path("M3.75 2.75h16.5v18.5H3.75zM7 6.5h2m2 0h2m2 0h2M7 10h2m2 0h2m2 0h2M7 13.5h2m2 0h2m2 0h2");
}

</style>
