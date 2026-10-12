<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xtlbptbid"/><path class="na8us16sm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cement-bag-sharp" {...props}></Icon>
<style>
:global(.na8us16sm) {
  d: path("M8 11h8v6H8z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xtlbptbid) {
  d: path("M5.5 5.75h13l1.25 14l.313 1.532l-1.563-.032h-13l-1.563.032l.313-1.532Zm0 0l1-3h11l1 3");
}

</style>
