<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mwe-9d8rn"/><circle class="hx-rxnbzw"/><circle class="m7thmobns"/><path class="cpuytsbrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:binary-tree" {...props}></Icon>
<style>
:global(.cpuytsbrt) {
  d: path("m11.28 7.37l-3.56 9.26m5-9.26l3.56 9.26");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hx-rxnbzw) {
  cx: 7px;
  cy: 18.5px;
  r: 2px;
}

:global(.m7thmobns) {
  cx: 17px;
  cy: 18.5px;
  r: 2px;
}

:global(.mwe-9d8rn) {
  cx: 12px;
  cy: 5.5px;
  r: 2px;
}

</style>
