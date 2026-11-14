<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hyku-5b5n"/><path class="xrq70cbzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dropdown" {...props}></Icon>
<style>
:global(.hyku-5b5n) {
  d: path("M2.5 6h19v12h-19ZM6 12h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xrq70cbzc) {
  d: path("m15 10.75l2 2l2-2");
}

</style>
