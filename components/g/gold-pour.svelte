<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h_plg4s9u"/><path class="e8rry7ekn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gold-pour" {...props}></Icon>
<style>
:global(.e8rry7ekn) {
  d: path("m7 15.5l1.5 5h11l1.5-5");
}

:global(.h_plg4s9u) {
  d: path("m12.5 6.5l-3.75 4.75l-5.25-3l2-5.75Zm0 0Q14 8 14 10.5v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
