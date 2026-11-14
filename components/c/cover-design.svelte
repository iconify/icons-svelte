<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="nhg2r0btc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cover-design" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n13x6dbmu) {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

:global(.nhg2r0btc) {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M10.75 6h3.5A1.75 1.75 0 0 1 16 7.75v3a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 9 10.75v-3A1.75 1.75 0 0 1 10.75 6");
}

</style>
