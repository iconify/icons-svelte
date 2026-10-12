<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rlp_7mbtl"/><path class="r866nrb5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quarantine-sharp" {...props}></Icon>
<style>
:global(.r866nrb5z) {
  d: path("M8 17.25a4 4 0 0 1 8 0Zm5.61-14.36a9.25 9.25 0 0 1 5.48 3.16m1.6 2.79a9.25 9.25 0 0 1 0 6.32m-1.6 2.79a9.25 9.25 0 0 1-5.48 3.16m-3.22 0a9.25 9.25 0 0 1-5.48-3.16m-1.6-2.79a9.25 9.25 0 0 1 0-6.32m1.6-2.79a9.25 9.25 0 0 1 5.48-3.16");
}

:global(.rlp_7mbtl) {
  cx: 12px;
  cy: 8.5px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
