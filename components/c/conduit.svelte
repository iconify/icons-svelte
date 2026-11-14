<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2a7-ybvz"/><path class="xkc4h9bgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:conduit" {...props}></Icon>
<style>
:global(.o2a7-ybvz) {
  d: path("M3 20.5h9a8 8 0 0 0 8-8V7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xkc4h9bgz) {
  d: path("M3 15.5h9a3 3 0 0 0 3-3V7M3 15.5v5m10.75-17h7.5V7h-7.5Z");
}

</style>
