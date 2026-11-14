<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ef4m474on"/><path class="hp_y2cg9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nature-reserve-map" {...props}></Icon>
<style>
:global(.ef4m474on) {
  d: path("m2.5 5.5l4.25-2l10.5 2l4.25-2v15l-4.25 2l-10.5-2l-4.25 2Zm4.25-2v15m10.5-13v15");
}

:global(.hp_y2cg9g) {
  d: path("m12 7.5l2.5 8h-5Zm0 8V17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
