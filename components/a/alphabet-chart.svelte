<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn70qi2py"/><path class="xhu2g2bbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:alphabet-chart" {...props}></Icon>
<style>
:global(.bn70qi2py) {
  d: path("M7.125 6h9.75A2.625 2.625 0 0 1 19.5 8.625v10.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875V8.625A2.625 2.625 0 0 1 7.125 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xhu2g2bbd) {
  d: path("M10.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M8 18.5L12 9l4 9.5M9.5 15h5");
}

</style>
