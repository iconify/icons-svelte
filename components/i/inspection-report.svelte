<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4m3qbbmk"/><path class="j4_i6obxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:inspection-report" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4_i6obxf) {
  d: path("m9 7.5l1 1l2-2m1.75 1h2.75M9 12l1 1l2-2m1.75 1h2.75M9 16.5l1 1l2-2m1.75 1h2.75");
}

:global(.p4m3qbbmk) {
  d: path("M7.125 2.5h9.75A2.625 2.625 0 0 1 19.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875V5.125A2.625 2.625 0 0 1 7.125 2.5M6.75 4.75v2m0 10.5v2");
}

</style>
