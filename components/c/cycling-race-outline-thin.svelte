<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jfpnmxb4i"/><path class="sebrrz16i"/><path class="sby6clb1g"/><path class="btevwoo0v"/><path class="rckmicclj"/><path class="laxf09b_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cycling-race-outline-thin" {...props}></Icon>
<style>
:global(.btevwoo0v) {
  d: path("m18 15 -7 -7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jfpnmxb4i) {
  d: path("M2 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.laxf09b_c) {
  d: path("m13 8 2 -2");
}

:global(.rckmicclj) {
  d: path("M14 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.sby6clb1g) {
  d: path("m6 15 7 -7");
}

:global(.sebrrz16i) {
  d: path("M14 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
