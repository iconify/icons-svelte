<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwusz1b0p"/><rect class="lr47v9xiv"/><circle class="zanv7q--q"/><circle class="pjrb6zm3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parade-float" {...props}></Icon>
<style>
:global(.cwusz1b0p) {
  d: path("m12.14 3.07l.69 1.53q.14.32.49.35l1.66.18q.35.04.09.27l-1.24 1.13q-.26.23-.19.57l.35 1.64q.07.34-.24.17l-1.45-.84q-.3-.17-.6 0l-1.45.84q-.31.17-.24-.17l.35-1.64q.07-.34-.19-.57L8.93 5.4q-.26-.23.09-.27l1.66-.18q.35-.03.49-.35l.69-1.53q.14-.32.28 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lr47v9xiv) {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 11.25px;
  rx: 1.5px;
}

:global(.pjrb6zm3p) {
  cx: 17px;
  cy: 19.75px;
  r: 1.5px;
}

:global(.zanv7q--q) {
  cx: 7px;
  cy: 19.75px;
  r: 1.5px;
}

</style>
