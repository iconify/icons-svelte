<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a417gfbbs"/><path class="a4gbf3bzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frequency" {...props}></Icon>
<style>
:global(.a417gfbbs) {
  d: path("M3 9.5q2.25-7.875 4.5 0t4.5 0t4.5 0t4.5 0");
}

:global(.a4gbf3bzs) {
  d: path("M3 16.5v2h9v-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
