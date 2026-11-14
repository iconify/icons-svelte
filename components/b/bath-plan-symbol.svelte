<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhuvow97a"/><path class="zbm237cvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bath-plan-symbol" {...props}></Icon>
<style>
:global(.mhuvow97a) {
  d: path("M2.5 5.5h19v13h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zbm237cvn) {
  d: path("M5.25 8.25h13.5v7.5H5.25ZM15.5 12h.01");
}

</style>
