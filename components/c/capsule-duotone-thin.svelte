<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1q7nzbdi"/><path class="u-mqtjbzo"/><path class="l0v-b4kbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:capsule-duotone-thin" {...props}></Icon>
<style>
:global(.h1q7nzbdi) {
  fill: currentColor;
  d: path("M8 7a4 4 0 0 1 8 0v10a4 4 0 0 1 -8 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.u-mqtjbzo) {
  d: path("M8 7a4 4 0 0 1 8 0v10a4 4 0 0 1 -8 0Z");
}

</style>
