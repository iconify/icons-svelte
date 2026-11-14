<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pphsu-i_k"/><path class="hii2-cc5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:body-wrap" {...props}></Icon>
<style>
:global(.hii2-cc5r) {
  d: path("M3 12a3 5 0 1 0 6 0a3 5 0 1 0-6 0Zm9.5-5v10m3-10v10M6 12h.01");
}

:global(.pphsu-i_k) {
  d: path("M6 7h12.5a2.5 5 0 0 1 0 10H6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
