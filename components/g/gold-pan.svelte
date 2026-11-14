<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkp-6rbik"/><path class="wrgoypa-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gold-pan" {...props}></Icon>
<style>
:global(.dkp-6rbik) {
  d: path("M2.5 10a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wrgoypa-q) {
  d: path("M3.5 12.25C4.5 17.5 8 19.5 12 19.5s7.5-2 8.5-7.25M9 10h.01m3.49-1h.01m1.99 2.5h.01");
}

</style>
