<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh350n3eh"/><path class="f15d-ccoo"/><path class="dxazypbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anticline" {...props}></Icon>
<style>
:global(.dxazypbqx) {
  d: path("M10.5 19.5c0-9 3-9 3 0m-11 0h19");
}

:global(.f15d-ccoo) {
  d: path("M6.5 19.5c0-14.5 11-14.5 11 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oh350n3eh) {
  d: path("M2.5 19.5c0-19.5 19-19.5 19 0");
}

</style>
