<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7pw-_b2k"/><path class="wj8hgmbzi"/><path class="j_sernfgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:employee-contribution" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_sernfgs) {
  d: path("m16 7l2 2l2-2");
}

:global(.n7pw-_b2k) {
  d: path("M4 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 17c0-3.25 2-5.25 4.5-5.25s4.5 2 4.5 5.25m3-3.5a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0");
}

:global(.wj8hgmbzi) {
  d: path("M14.5 13.5V19a3.5 1.75 0 0 0 7 0v-5.5M13 5h5v4");
}

</style>
