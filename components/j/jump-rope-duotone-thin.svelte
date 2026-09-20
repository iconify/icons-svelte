<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="umge8xb0s"/><path class="fkvuv9bip"/><path class="zxrz0obcn"/><path class="eguxbnz0i"/><path class="a3zqh3bcj"/><path class="he6b77rju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jump-rope-duotone-thin" {...props}></Icon>
<style>
:global(.a3zqh3bcj) {
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.eguxbnz0i) {
  d: path("M20 10a8 8 0 0 1 -16 0");
}

:global(.fkvuv9bip) {
  fill: currentColor;
  d: path("M18 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.he6b77rju) {
  d: path("M18 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umge8xb0s) {
  fill: currentColor;
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zxrz0obcn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 10a8 8 0 0 1 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
