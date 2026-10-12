<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ux32n0bfz"/><circle class="xftpa2b-b"/><circle class="psk4tbz5v"/><circle class="lggwgsh6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-bubble" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lggwgsh6t) {
  cx: 17.5px;
  cy: 16px;
  r: 1.5px;
}

:global(.psk4tbz5v) {
  cx: 15.25px;
  cy: 8.75px;
  r: 3.25px;
}

:global(.ux32n0bfz) {
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5");
}

:global(.xftpa2b-b) {
  cx: 9.25px;
  cy: 14.25px;
  r: 2px;
}

</style>
