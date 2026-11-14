<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="scntx542r"/><path class="zu3a0rlzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gyroscope" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.scntx542r) {
  d: path("M4 11a8 8 0 1 0 16 0a8 8 0 1 0-16 0m8-8.75V21.5m-3.5 0h7");
}

:global(.zu3a0rlzi) {
  d: path("M7 11a5 2.75 0 1 0 10 0a5 2.75 0 1 0-10 0");
}

</style>
