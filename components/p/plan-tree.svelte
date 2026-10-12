<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esaucociw"/><circle class="e9-7-8-2z"/><circle class="qparmibsf"/><circle class="vzfjefbad"/><circle class="ccs1kmb8v"/><circle class="gw7frccqd"/><circle class="ye6maf4he"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:plan-tree" {...props}></Icon>
<style>
:global(.ccs1kmb8v) {
  cx: 4.75px;
  cy: 19.25px;
  r: 2px;
}

:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.esaucociw) {
  d: path("m10.95 6.45l-2.4 3.85m4.66-3.96l3.08 4.07m-9.5 3.46l-1.33 3.51m2.75-3.51l1.33 3.51M17.5 14v3.25");
}

:global(.gw7frccqd) {
  cx: 10.25px;
  cy: 19.25px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qparmibsf) {
  cx: 7.5px;
  cy: 12px;
  r: 2px;
}

:global(.vzfjefbad) {
  cx: 17.5px;
  cy: 12px;
  r: 2px;
}

:global(.ye6maf4he) {
  cx: 17.5px;
  cy: 19.25px;
  r: 2px;
}

</style>
