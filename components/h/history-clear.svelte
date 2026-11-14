<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mk5xfob2d"/><path class="k2jw7rt-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:history-clear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2jw7rt-z) {
  d: path("m2 9l3 3l3-3m2.5.5l5 5m0-5l-5 5");
}

:global(.mk5xfob2d) {
  d: path("M5 12a8 8 0 1 1 4 6.928");
}

</style>
