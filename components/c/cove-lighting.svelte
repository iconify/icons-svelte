<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ks5z5peas"/><path class="hszjllbvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cove-lighting" {...props}></Icon>
<style>
:global(.hszjllbvx) {
  d: path("M3 14h8v-2M7 9.5L6 6m3.75 3.5l1-3.5m1.75 4l3-3");
}

:global(.ks5z5peas) {
  d: path("M21.5 3H3v18.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
