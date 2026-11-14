<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t9yztfbak"/><path class="b2y0vsb-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kpi-flat" {...props}></Icon>
<style>
:global(.b2y0vsb-k) {
  d: path("M13.25 11.75L15 13.5l-1.75 1.75");
}

:global(.t9yztfbak) {
  d: path("M2.5 3h19v18h-19ZM6 6.75h5M6 13.5h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
