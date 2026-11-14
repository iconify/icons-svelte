<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ae2hq-bsy"/><path class="suklk_vnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:galley-kitchen" {...props}></Icon>
<style>
:global(.ae2hq-bsy) {
  d: path("M2.5 2.5h8v19h-8Zm13.5 0h5.5v19H16Z");
}

:global(.suklk_vnw) {
  d: path("M5 6h3v5.5H5ZM2.5 8.75H5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
