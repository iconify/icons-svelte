<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qm03awwls"/><path class="f7bnl_b6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-mountain" {...props}></Icon>
<style>
:global(.f7bnl_b6k) {
  d: path("m7.5 10l2.5 2l2.5-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qm03awwls) {
  d: path("m3 19l7-14l4 8l2.5-4l5 10Z");
}

</style>
