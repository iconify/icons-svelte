<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hp9ld3byv"/><path class="yq73u1b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:query-editor" {...props}></Icon>
<style>
:global(.hp9ld3byv) {
  d: path("M2.5 3.5h19v17h-19Zm0 4.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yq73u1b8c) {
  d: path("M5 10.5L7 12l-2 1.5M9 12h8m-6 4.5h3.5m2-2v4");
}

</style>
