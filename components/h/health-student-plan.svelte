<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2yzaf44i"/><path class="ppub1ebcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:health-student-plan" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2yzaf44i) {
  d: path("m12.699 4.368l6.279 3.305a1.5 1.5 0 0 1 0 2.654l-6.279 3.305a1.5 1.5 0 0 1-1.398 0l-6.279-3.305a1.5 1.5 0 0 1 0-2.654l6.279-3.305a1.5 1.5 0 0 1 1.398 0");
}

:global(.ppub1ebcp) {
  d: path("M6 11.5V16c0 1.5 2.5 3 6 3s6-1.5 6-3v-4.5M21.5 9v6");
}

</style>
