<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mupo5fbhr"/><path class="ehib3abci"/><path class="fhs8z1bjw"/><path class="fduloacov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exam-hall-outline-thin" {...props}></Icon>
<style>
:global(.ehib3abci) {
  d: path("M15 8h6v4h-6Z");
}

:global(.fduloacov) {
  d: path("M15 16h6v4h-6Z");
}

:global(.fhs8z1bjw) {
  d: path("M3 16h6v4H3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mupo5fbhr) {
  d: path("M3 8h6v4H3Z");
}

</style>
