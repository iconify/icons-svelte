<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8xrxkbnm"/><path class="iggzz_quh"/><path class="ol-k0xutu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ar-navigation" {...props}></Icon>
<style>
:global(.h8xrxkbnm) {
  d: path("M7.5 4.5h9l5 15.5h-19Z");
}

:global(.iggzz_quh) {
  d: path("M10.5 17v-5a2 2 0 0 1 2-2H15");
}

:global(.ol-k0xutu) {
  d: path("m13 8l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
