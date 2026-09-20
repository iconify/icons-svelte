<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="svccqbc_g"/><path class="y--9wccrh"/><path class="pkfzzlbbg"/><path class="jwxgs0b2c"/><path class="v4hj5197o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-light-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jwxgs0b2c) {
  d: path("m11 9 4 -4");
}

:global(.pkfzzlbbg) {
  d: path("M11 9v11");
}

:global(.svccqbc_g) {
  fill: currentColor;
  d: path("M10 9h8l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v4hj5197o) {
  d: path("M10 9h8l-4 4Z");
}

:global(.y--9wccrh) {
  d: path("M5 20h12");
}

</style>
