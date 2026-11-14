<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mp298383d"/><path class="l6tkhlb_v"/><path class="b6x2k4k2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:metal-coil" {...props}></Icon>
<style>
:global(.b6x2k4k2i) {
  d: path("M8 11.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.l6tkhlb_v) {
  d: path("M17 11.5a6 6 0 1 1-6-6");
}

:global(.mp298383d) {
  d: path("M2 11.5a9 9 0 1 0 18 0a9 9 0 1 0-18 0Zm9 9h10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
