<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ysirmiopq"/><path class="vj_k0qhap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:diaper" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vj_k0qhap) {
  fill: currentColor;
  d: path("M2.5 4.75h2v3.5h-2Zm17 0h2v3.5h-2Z");
}

:global(.ysirmiopq) {
  d: path("M3.5 5.5h17V10c-3.25.5-5.5 3.5-6 8.5h-5c-.5-5-2.75-8-6-8.5Zm0 2.5h17");
}

</style>
