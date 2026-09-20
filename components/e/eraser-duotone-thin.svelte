<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="me9dqjepj"/><path class="jhq2fxlof"/><path class="rsvh7b0ab"/><path class="uk_l5kxob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:eraser-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jhq2fxlof) {
  d: path("m3 15 6 -6h12l-6 6Z");
}

:global(.me9dqjepj) {
  fill: currentColor;
  d: path("m3 15 6 -6h12l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rsvh7b0ab) {
  d: path("M3 15v4h12l6 -6V9");
}

:global(.uk_l5kxob) {
  d: path("M9 9v4l-6 6");
}

</style>
