<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zv28i2bwu"/><path class="ubya92box"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:moat-drawbridge" {...props}></Icon>
<style>
:global(.ubya92box) {
  d: path("M9 18v-5a3 3 0 0 1 6 0v5m-6 0h6l2.5 3.5h-11Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zv28i2bwu) {
  d: path("M4.5 18V2.5h3V5h3V2.5h3V5h3V2.5h3V18Z");
}

</style>
