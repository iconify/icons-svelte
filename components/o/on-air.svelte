<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r3_1npb-l"/><circle class="m1is5jemp"/><path class="z0qge-b2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:on-air" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1is5jemp) {
  cx: 7.75px;
  cy: 12px;
  r: 2px;
}

:global(.r3_1npb-l) {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 7.5px;
  rx: 2.5px;
}

:global(.z0qge-b2w) {
  d: path("M12.25 12h5.5");
}

</style>
