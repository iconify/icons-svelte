<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wn3aa3jhs"/><path class="e4clx_akv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:car-hood" {...props}></Icon>
<style>
:global(.e4clx_akv) {
  d: path("M14.5 10c1.5-3 4-4.5 7-4.5M20 10V5.75M5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wn3aa3jhs) {
  d: path("M2.5 15.5V11a1 1 0 0 1 1-1H5l3-4.5h4l2.5 4.5h6a1 1 0 0 1 1 1v4.5Z");
}

</style>
