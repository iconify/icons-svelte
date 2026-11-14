<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zc_jjc_ve"/><path class="sfcrlxr5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:review-thread" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sfcrlxr5f) {
  d: path("M8 6.25V4.5a2 2 0 0 1 2-2h9.5a2 2 0 0 1 2 2V16l-2.75-3");
}

:global(.zc_jjc_ve) {
  d: path("M2.5 11a2 2 0 0 1 2-2H14a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8.5L5 21.5V19h-.5a2 2 0 0 1-2-2Z");
}

</style>
