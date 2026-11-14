<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l73pdpbsu"/><path class="fksyncb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:health-trends" {...props}></Icon>
<style>
:global(.fksyncb1r) {
  d: path("m6 17l3-2h1.25l1-5l1.5 7.5l1-4.5L16 11.5L20.5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l73pdpbsu) {
  d: path("M3.5 2.5v18h18");
}

</style>
