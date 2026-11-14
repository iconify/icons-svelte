<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oiw-qyb_h"/><path class="ar6h56e9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-curve-up-right" {...props}></Icon>
<style>
:global(.ar6h56e9e) {
  d: path("M11 3h5v5");
}

:global(.oiw-qyb_h) {
  d: path("M8 21v-7c0-2 .75-3.75 2-5l6-6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
