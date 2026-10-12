<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="pmijk-bgh"/><path class="zucgc5b1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fire-extinguisher-sign" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pmijk-bgh) {
  d: path("M10 18.25V10.5a2 2 0 0 1 4 0v7.75Z");
}

:global(.zucgc5b1u) {
  d: path("M12 8.5V6m-1.75 0h3.5l1.75 1.25c1.25.75 1.75 2 1.75 3.5V15");
}

</style>
