<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m47-sobua"/><path class="b_uynac9f"/><path class="ejqpu233w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:amphitheatre-stage" {...props}></Icon>
<style>
:global(.b_uynac9f) {
  d: path("M5 13.5a7 5.5 0 0 1 14 0");
}

:global(.ejqpu233w) {
  d: path("M2.5 13.5a9.5 8.5 0 0 1 19 0m-15 2.75h11v3h-11Z");
}

:global(.m47-sobua) {
  d: path("M7.75 13.5a4.25 2.75 0 0 1 8.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
