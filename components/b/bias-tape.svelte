<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyqsp1igo"/><path class="y79v70b_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bias-tape" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pyqsp1igo) {
  d: path("M9 15.5a6.5 6.5 0 1 1 0-13a6.5 6.5 0 0 1 0 13h8.5l3.5 5h-8.5Z");
}

:global(.y79v70b_o) {
  d: path("M6.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
