<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w9elh_16j"/><path class="eykhj5x6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:call-centre-headset" {...props}></Icon>
<style>
:global(.eykhj5x6m) {
  d: path("M3.25 12h3.5v6h-3.5Zm14 0h3.5v6h-3.5ZM5 18q0 3.5 4.5 3.5H12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w9elh_16j) {
  d: path("M5 13v-2a7 7 0 0 1 14 0v2");
}

</style>
