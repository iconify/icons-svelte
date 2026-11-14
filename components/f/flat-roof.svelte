<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dykh2zrig"/><path class="w4puj2l2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flat-roof" {...props}></Icon>
<style>
:global(.dykh2zrig) {
  d: path("M4 4h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 7H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 4m.5 3v14.5h15V7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w4puj2l2z) {
  d: path("M10.5 21.5v-5h3v5m-5-11.75h7a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5m3.5 0v3.5");
}

</style>
