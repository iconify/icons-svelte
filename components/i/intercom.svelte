<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hg15ysbqv"/><path class="plksdhbjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:intercom" {...props}></Icon>
<style>
:global(.hg15ysbqv) {
  d: path("M9.5 2.5h5A3.5 3.5 0 0 1 18 6v12a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18V6a3.5 3.5 0 0 1 3.5-3.5M9 6h6M9 8.75h6M9 11.5h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.plksdhbjo) {
  d: path("M10 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
