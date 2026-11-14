<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t-peadbli"/><path class="g6-inz88q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:open-house" {...props}></Icon>
<style>
:global(.g6-inz88q) {
  d: path("M15.5 6.5v-3H18v5M9 14h4.5v7H9Zm0 0l-4.25-1.75v7.25L9 21Z");
}

:global(.t-peadbli) {
  d: path("m3 11l9-7.5l9 7.5v10H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
