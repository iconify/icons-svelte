<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="etgb8acgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caret-left-circle" {...props}></Icon>
<style>
:global(.etgb8acgb) {
  d: path("M10.169 10.839L11.8 9.504a1.5 1.5 0 0 1 2.45 1.161v2.67a1.5 1.5 0 0 1-2.45 1.161l-1.631-1.335a1.5 1.5 0 0 1 0-2.322");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
