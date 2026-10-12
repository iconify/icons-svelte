<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a019a6jlz"/><rect class="b75k3_mqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:focus-ring" {...props}></Icon>
<style>
:global(.a019a6jlz) {
  d: path("M2.75 8.75v-1a2.5 2.5 0 0 1 2.5-2.5h1m11.5 0h1a2.5 2.5 0 0 1 2.5 2.5v1m0 6.5v1a2.5 2.5 0 0 1-2.5 2.5h-1m-11.5 0h-1a2.5 2.5 0 0 1-2.5-2.5v-1m7.25-10h4m-4 13.5h4");
}

:global(.b75k3_mqy) {
  width: 11.5px;
  height: 6.5px;
  x: 6.25px;
  y: 8.75px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
