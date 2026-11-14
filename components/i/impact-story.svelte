<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-ma0bc_i"/><path class="lhawocb3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:impact-story" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lhawocb3f) {
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2 6.75c0-1.25 1.75-2 4-2s4 .75 4 2");
}

:global(.u-ma0bc_i) {
  d: path("M4.5 3h15a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2H10L5.5 21v-3.5h-1a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2");
}

</style>
