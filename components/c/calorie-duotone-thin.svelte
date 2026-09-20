<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zjk8l6bef"/><path class="hthehj4ml"/><path class="u4sowhi7h"/><path class="a0lcnrc-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:calorie-duotone-thin" {...props}></Icon>
<style>
:global(.a0lcnrc-j) {
  d: path("M18 16a6 6 0 0 1 -12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hthehj4ml) {
  d: path("M12 3c1.5 3 4 4 4 7a4 4 0 1 1 -8 0c0 -2.5 2 -3 2 -4.5 0.5 1 2 1 2 -2.5");
}

:global(.u4sowhi7h) {
  d: path("M4 16h16");
}

:global(.zjk8l6bef) {
  fill: currentColor;
  d: path("M12 3c1.5 3 4 4 4 7a4 4 0 1 1 -8 0c0 -2.5 2 -3 2 -4.5 0.5 1 2 1 2 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
