<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="j0_lc_r7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-epub-sharp" {...props}></Icon>
<style>
:global(.j0_lc_r7y) {
  d: path("M13.75 2.75v5.5h5.5m-7.25 4v6m0-6l-1.333-1H8.25v6h2.417l1.333 1l1.333-1h2.417v-6h-2.417l-1.333 1");
}

:global(.rh2140hgr) {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
