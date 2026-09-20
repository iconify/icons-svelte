<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rl0mwnbkl"/><path class="sojjg40ea"/><path class="l3yb7ybjz"/><path class="kz82t0nla"/><path class="gy18-zqeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prism-duotone-thin" {...props}></Icon>
<style>
:global(.gy18-zqeb) {
  d: path("M14 19h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kz82t0nla) {
  d: path("M14 15h7");
}

:global(.l3yb7ybjz) {
  d: path("M2 9h6");
}

:global(.rl0mwnbkl) {
  fill: currentColor;
  d: path("m12 5 7 7H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sojjg40ea) {
  d: path("m12 5 7 7H5Z");
}

</style>
