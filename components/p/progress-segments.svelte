<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s-5urxb6y"/><path class="n8_m05bbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:progress-segments" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n8_m05bbi) {
  d: path("M19.375 8za2.125 2.125 0 0 1 2.125 2.125v3.75A2.125 2.125 0 0 1 19.375 16a2.125 2.125 0 0 1-2.125-2.125v-3.75A2.125 2.125 0 0 1 19.375 8");
}

:global(.s-5urxb6y) {
  fill: currentColor;
  d: path("M4.875 8zA2.125 2.125 0 0 1 7 10.125v3.75A2.125 2.125 0 0 1 4.875 16a2.125 2.125 0 0 1-2.125-2.125v-3.75A2.125 2.125 0 0 1 4.875 8m7.25 0za2.125 2.125 0 0 1 2.125 2.125v3.75A2.125 2.125 0 0 1 12.125 16A2.125 2.125 0 0 1 10 13.875v-3.75A2.125 2.125 0 0 1 12.125 8");
}

</style>
