<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hb7moqkly"/><path class="lfem3dbxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:burst-mode-sharp" {...props}></Icon>
<style>
:global(.hb7moqkly) {
  d: path("M2.75 8.75v6.5m3-8.5v10.5m3-12.5h12.5v14.5H8.75z");
}

:global(.lfem3dbxp) {
  d: path("M18 12a3 3 0 1 1-6 0a3 3 0 1 1 6 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
