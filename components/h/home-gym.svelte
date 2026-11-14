<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qu1fttbcf"/><path class="lapfsxe-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:home-gym" {...props}></Icon>
<style>
:global(.lapfsxe-b) {
  d: path("M6 11.25V7a2.5 2.5 0 0 1 2.5-2.5h7A2.5 2.5 0 0 1 18 7v4.25M8.75 15.5A3.5 3.5 0 0 1 11 12.25");
}

:global(.qu1fttbcf) {
  d: path("M9 20.5a6.75 6.75 0 1 1 6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
