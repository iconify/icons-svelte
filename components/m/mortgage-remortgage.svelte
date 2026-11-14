<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mvq88gbfh"/><path class="db0t-jucs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-remortgage" {...props}></Icon>
<style>
:global(.db0t-jucs) {
  d: path("M16 7V4h2v4.75m-3 7.5h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

:global(.mvq88gbfh) {
  d: path("M11.86 20.5H4v-10l8-7l8 7v.84");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
