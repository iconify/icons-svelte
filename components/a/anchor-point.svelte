<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dd2fi97pf"/><rect class="ws4hpbvoz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:anchor-point" {...props}></Icon>
<style>
:global(.dd2fi97pf) {
  d: path("M3 20.75L10.25 11m4.25-2.5h6.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ws4hpbvoz) {
  width: 5px;
  height: 5px;
  x: 9.5px;
  y: 6px;
  rx: 0.75px;
}

</style>
