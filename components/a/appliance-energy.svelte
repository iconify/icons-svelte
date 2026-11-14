<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m-eufxfsq"/><path class="urb3q6-4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:appliance-energy" {...props}></Icon>
<style>
:global(.m-eufxfsq) {
  d: path("M11.6 19H2.5V2.5H18v8.7M2.5 7.5H18M6 5h.01M9.5 5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.urb3q6-4i) {
  d: path("M14.4 15.5H6V11h8.5v4.4m5-1.65L16 18h3.5L17 21.75");
}

</style>
