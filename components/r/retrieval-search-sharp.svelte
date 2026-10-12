<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="y-fd6pbmc"/><path class="gnwvme3cw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:retrieval-search-sharp" {...props}></Icon>
<style>
:global(.gnwvme3cw) {
  d: path("M15.6 15.6L21 21M10.25 6.25q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y-fd6pbmc) {
  cx: 10.25px;
  cy: 10.25px;
  r: 7.5px;
}

</style>
