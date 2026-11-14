<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ap2dmzunj"/><path class="exggwzbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bucket-versioning" {...props}></Icon>
<style>
:global(.ap2dmzunj) {
  d: path("m3 6l2 13.5q.25 1 1.5 1h5.25m5.253-7.773L18 6");
}

:global(.exggwzbgh) {
  d: path("M3 6a7.5 2.5 0 1 0 15 0A7.5 2.5 0 1 0 3 6Zm12.25 10.75l3-1.5l3 1.5l-3 1.5Zm0 3l3 1.5l3-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
