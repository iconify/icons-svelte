<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-rm4cbrd"/><path class="myi7s5bkj"/><circle class="s-ijl8b-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hearing-aid" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.myi7s5bkj) {
  d: path("M13.25 5C9 4.75 7.25 8.25 8 13.25");
}

:global(.p-rm4cbrd) {
  d: path("M15.75 3a3.5 3.5 0 0 1 3.5 3.5c0 4.25-1.5 8.5-4.5 8.5a1.75 1.75 0 0 1-1.5-2.5c1-2 1-3.75.25-5.5a2.75 2.75 0 0 1 2.25-4");
}

:global(.s-ijl8b-g) {
  cx: 8px;
  cy: 15px;
  r: 1.75px;
}

</style>
