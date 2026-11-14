<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zijoocb-r"/><path class="k1nly_hgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kitchen-range" {...props}></Icon>
<style>
:global(.k1nly_hgn) {
  d: path("M7.5 6.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm7 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-7 6h9v5h-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zijoocb-r) {
  d: path("M4 3.5h16v17H4Zm0 6h16");
}

</style>
