<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxvzxibbq"/><path class="gmim_3b_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magnetic-poles" {...props}></Icon>
<style>
:global(.gmim_3b_e) {
  fill: currentColor;
  d: path("M14.5 16h5v4.5h-5Z");
}

:global(.sxvzxibbq) {
  d: path("M4.5 20.5V10a7.5 7.5 0 0 1 15 0v10.5h-5V10a2.5 2.5 0 0 0-5 0v10.5Zm0-4.5h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
