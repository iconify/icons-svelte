<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r_d15_b6i"/><path class="j-qrtmxgs"/><path class="e8hdfoncf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:red-envelope-sharp" {...props}></Icon>
<style>
:global(.e8hdfoncf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15h.01");
}

:global(.j-qrtmxgs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 7l6 4l6-4");
}

:global(.r_d15_b6i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12v18H6z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
