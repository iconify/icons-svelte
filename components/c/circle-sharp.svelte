<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qa4zveyod"/><path class="psv3yebmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:circle-sharp" {...props}></Icon>
<style>
:global(.psv3yebmi) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 14h.01");
}

:global(.qa4zveyod) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18.75V3.517l1.76.073a17 17 0 0 1 15.15 15.15l.073 1.76H3.5z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
