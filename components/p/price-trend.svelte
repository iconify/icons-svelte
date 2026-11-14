<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jn05a6lxy"/><path class="v0jk3oopn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:price-trend" {...props}></Icon>
<style>
:global(.jn05a6lxy) {
  d: path("m3 17l5.5-6l4 3.5l8-8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v0jk3oopn) {
  d: path("M16 6h4.5v4.5");
}

</style>
