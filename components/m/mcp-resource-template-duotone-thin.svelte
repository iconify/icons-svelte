<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pux-8e3tz"/><path class="cacmi2bmi"/><path class="jtt8g10_o"/><path class="ikiprn9sq"/><path class="g31q_jb0h"/><path class="zrsj1cc7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-resource-template-duotone-thin" {...props}></Icon>
<style>
:global(.cacmi2bmi) {
  d: path("M13 3H9L6 6v15h12V8");
}

:global(.g31q_jb0h) {
  d: path("M9 10v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.pux-8e3tz) {
  fill: currentColor;
  d: path("M13 3H9L6 6v15h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zrsj1cc7l) {
  d: path("M15 10v4");
}

</style>
