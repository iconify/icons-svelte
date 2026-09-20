<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="mmi5hvbvz"/><path class="c6jnv7x8o"/><path class="y1_flyglu"/><path class="ws9v8zbhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:policy-outline-thin" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.c6jnv7x8o) {
  d: path("M11 10h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mmi5hvbvz) {
  d: path("M9 8v10");
}

:global(.ws9v8zbhe) {
  d: path("M11 16h6");
}

:global(.y1_flyglu) {
  d: path("M11 13h6");
}

</style>
