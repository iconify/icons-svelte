<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o0sjnxbzj"/><path class="pd_u6ybei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:golden-ratio-sharp" {...props}></Icon>
<style>
:global(.o0sjnxbzj) {
  d: path("M3 6h18v11H3zm11 0v11");
}

:global(.pd_u6ybei) {
  d: path("M6 17a8 8 0 0 1 8-8");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
