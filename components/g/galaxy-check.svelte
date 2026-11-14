<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bye8libtl"/><path class="t-gm85b-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:galaxy-check" {...props}></Icon>
<style>
:global(.bye8libtl) {
  d: path("M10.5 10.5h.01m3.49 0c0-4.75-6.5-6-9.5-3c-2.5 2.5-2 6.5.5 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t-gm85b-x) {
  d: path("M7 10.5c0 4.75 6.5 6 9.5 3c2.5-2.5 2-6.5-.5-9M14.75 18l2 2L21 15.75");
}

</style>
