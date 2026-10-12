<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zwb_hob4q"/><path class="jx-dnfdjc"/><circle class="n1yo2g4qm"/><path class="gczibjbob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:playdate" {...props}></Icon>
<style>
:global(.gczibjbob) {
  d: path("M15 21.25v-5.5a3 3 0 0 1 6 0v5.5ZM9 15.5l3 2.5l3-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jx-dnfdjc) {
  d: path("M3 21.25v-5.5a3 3 0 0 1 6 0v5.5Z");
}

:global(.n1yo2g4qm) {
  cx: 18px;
  cy: 7.75px;
  r: 2px;
}

:global(.zwb_hob4q) {
  cx: 6px;
  cy: 7.75px;
  r: 2px;
}

</style>
