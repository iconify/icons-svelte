<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezknac2uj"/><path class="i5pxp64df"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:embossing-stylus" {...props}></Icon>
<style>
:global(.ezknac2uj) {
  d: path("M2.5 19h6a3.5 3.5 0 0 1 7 0h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i5pxp64df) {
  d: path("M10.5 14a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m2.5-1l2.75-2.75m4.975-4.975za1.5 1.5 0 0 1 0 2.121l-2.829 2.829a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l2.829-2.829a1.5 1.5 0 0 1 2.121 0");
}

</style>
