<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="go4py7bii"/><rect class="yi810b21w"/><path class="aythsibbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:envelope-stack" {...props}></Icon>
<style>
:global(.aythsibbt) {
  d: path("m2.75 9.5l8 5.5l8-5.5");
}

:global(.go4py7bii) {
  d: path("M6 8.5v-2A1.5 1.5 0 0 1 7.5 5h12.25a1.5 1.5 0 0 1 1.5 1.5v10a1.5 1.5 0 0 1-1.5 1.5h-1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yi810b21w) {
  width: 16px;
  height: 12.75px;
  x: 2.75px;
  y: 8.5px;
  rx: 2px;
}

</style>
