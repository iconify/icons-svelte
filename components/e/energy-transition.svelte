<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="abi02fbuk"/><path class="q5xyx5bnm"/><path class="b31t3t6kn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy-transition" {...props}></Icon>
<style>
:global(.abi02fbuk) {
  d: path("M15.75 5.505A7.5 7.5 0 0 1 12 19.5");
}

:global(.b31t3t6kn) {
  d: path("m10 2.5l2 2l-2 2m2.75.75l-4.5 5.5h3.5l-.5 4l4.5-5.5h-3.5Z");
}

:global(.q5xyx5bnm) {
  d: path("m14 17.5l-2 2l2 2m-5.75-3.005A7.5 7.5 0 0 1 12 4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
