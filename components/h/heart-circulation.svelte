<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e81u8ubhx"/><path class="xddcc2bdh"/><path class="t5mofjtby"/><path class="qupeo_3fy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heart-circulation" {...props}></Icon>
<style>
:global(.e81u8ubhx) {
  d: path("m12 16.5l-3.75-3.75A2.65 2.65 0 0 1 12 9.25a2.65 2.65 0 0 1 3.75 3.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qupeo_3fy) {
  d: path("m10 2l2 2l-2 2");
}

:global(.t5mofjtby) {
  d: path("m14 18l-2 2l2 2m-6-3.072A8 8 0 0 1 12 4");
}

:global(.xddcc2bdh) {
  d: path("M16 5.072A8 8 0 0 1 12 20");
}

</style>
