<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gizk7zb8c"/><rect class="u_hqpzbnr"/><rect class="vai_3cb-o"/><path class="zazonob0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bed-hotel" {...props}></Icon>
<style>
:global(.gizk7zb8c) {
  d: path("M4.5 12V5.75A2.5 2.5 0 0 1 7 3.25h10a2.5 2.5 0 0 1 2.5 2.5V12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u_hqpzbnr) {
  width: 9px;
  height: 2.5px;
  x: 7.5px;
  y: 6.5px;
  rx: 1.25px;
}

:global(.vai_3cb-o) {
  width: 18.5px;
  height: 5.5px;
  x: 2.75px;
  y: 12px;
  rx: 1.5px;
}

:global(.zazonob0v) {
  d: path("M4.5 17.5v3.75m15-3.75v3.75");
}

</style>
