<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uhf74ebdy"/><path class="n0s8yb72i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:door-glass" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n0s8yb72i) {
  d: path("M10.25 5.5h3.5a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 8.5 9.75v-2.5a1.75 1.75 0 0 1 1.75-1.75m5.25 9V17");
}

:global(.uhf74ebdy) {
  d: path("M8.125 2.5h7.75A2.625 2.625 0 0 1 18.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 5.5 18.875V5.125A2.625 2.625 0 0 1 8.125 2.5");
}

</style>
