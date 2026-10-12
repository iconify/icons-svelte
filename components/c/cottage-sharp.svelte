<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bd969jbgx"/><path class="ikvuw6bzw"/><path class="g05czlb4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cottage-sharp" {...props}></Icon>
<style>
:global(.bd969jbgx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.35v-9.1l.65-.63l6.2-5.99L12 4l.65.63l1.7 1.64l.65.63V4.5h2.75v5.05l.65.63l.45.44l.65.63v10h-15z");
}

:global(.g05czlb4i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25V16h3.5v5.25");
}

:global(.ikvuw6bzw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
