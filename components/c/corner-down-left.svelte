<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxh-ftnjv"/><path class="dwwgy-e6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-down-left" {...props}></Icon>
<style>
:global(.dwwgy-e6i) {
  d: path("m9.5 9.5l-5 5l5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vxh-ftnjv) {
  d: path("M19.5 4.5V11a3.5 3.5 0 0 1-3.5 3.5H4.5");
}

</style>
