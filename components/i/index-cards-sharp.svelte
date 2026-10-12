<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bzyq96a0l"/><path class="ltj2t8cex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:index-cards-sharp" {...props}></Icon>
<style>
:global(.bzyq96a0l) {
  d: path("M6 8.5V5h15.25v13h-2.5");
}

:global(.ltj2t8cex) {
  d: path("M2.75 8.5h16v12.75h-16zm0 3.75h16m-13 3.25h10m-10 3h6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
