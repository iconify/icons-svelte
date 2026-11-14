<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hp9ld3byv"/><path class="vspokuu4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:query-result" {...props}></Icon>
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

:global(.vspokuu4u) {
  d: path("M6 11h12v6.5H6Zm4 0v6.5m4-6.5v6.5m-8-3.25h12");
}

</style>
