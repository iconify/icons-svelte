<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ycm3w5rua"/><path class="bw0pajw5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:package-tarball" {...props}></Icon>
<style>
:global(.bw0pajw5r) {
  d: path("M4 8.5v10a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-10m-10.5 4h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ycm3w5rua) {
  fill: currentColor;
  d: path("M2.5 3.5h19v5h-19Z");
}

</style>
