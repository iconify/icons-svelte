<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xtcet4b0b"/><path class="sge6w-ukl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:guardrail" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sge6w-ukl) {
  d: path("M6.25 8h11.5m-12 3.25v6.5m6.25-6.5v6.5m6.25-6.5v6.5M2.75 20.5h4m3.25 0h4m3.25 0h4");
}

:global(.xtcet4b0b) {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
