<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ps7jdmbef"/><path class="wqcz0s_3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dashboard-embed" {...props}></Icon>
<style>
:global(.ps7jdmbef) {
  d: path("M13.5 21.5h-11v-19h19V13m-19-2h19M11 11v10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wqcz0s_3d) {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5M16.5 15l-2 3l2 3m3-6l2 3l-2 3");
}

</style>
