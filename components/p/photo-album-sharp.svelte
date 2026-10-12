<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t77_dpr5q"/><path class="yce3cuw3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:photo-album-sharp" {...props}></Icon>
<style>
:global(.t77_dpr5q) {
  d: path("M3.75 2.75h16.5v18.5H3.75zm3.5 0v18.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yce3cuw3r) {
  d: path("M10.25 7.25h6.5v6h-6.5zm0 9.75h6.5");
}

</style>
