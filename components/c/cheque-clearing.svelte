<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dg0athhvc"/><path class="zjpa3ob-p"/><path class="m838ucczp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-clearing" {...props}></Icon>
<style>
:global(.dg0athhvc) {
  d: path("M11.2 18.5H2.5v-13h19v6.7M6 9.5h5.5m-5.5 5h3.5");
}

:global(.m838ucczp) {
  d: path("m15.5 12.25l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zjpa3ob-p) {
  d: path("M20.531 16a3.5 3.5 0 1 1-3.031-1.75");
}

</style>
