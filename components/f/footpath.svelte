<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyqln2b_q"/><circle class="zanv7q--q"/><path class="it605fbmt"/><circle class="f-7dtmabf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:footpath" {...props}></Icon>
<style>
:global(.f-7dtmabf) {
  cx: 17px;
  cy: 14.75px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it605fbmt) {
  d: path("M14.25 6.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0");
}

:global(.pyqln2b_q) {
  d: path("M4.25 11.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0");
}

:global(.zanv7q--q) {
  cx: 7px;
  cy: 19.75px;
  r: 1.5px;
}

</style>
