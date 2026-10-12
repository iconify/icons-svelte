<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="z0rxcxb0v"/><path class="lwx762bnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:packing-tape-sharp" {...props}></Icon>
<style>
:global(.lwx762bnj) {
  d: path("M6 9.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m3.25 6.5h12L20 17.5l1.25 1.75h-12Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0rxcxb0v) {
  cx: 9.25px;
  cy: 9.25px;
  r: 6.5px;
}

</style>
