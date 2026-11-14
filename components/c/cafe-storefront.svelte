<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="by0hub7oo"/><path class="zw_tpducc"/><path class="jji-18bll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cafe-storefront" {...props}></Icon>
<style>
:global(.by0hub7oo) {
  d: path("m3 9l1.5-5h15L21 9Zm0 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0");
}

:global(.jji-18bll) {
  d: path("M9 20.5V15h6v5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zw_tpducc) {
  d: path("M4.5 12v8.5h15V12");
}

</style>
