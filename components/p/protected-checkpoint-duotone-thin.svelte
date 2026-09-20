<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kysn4r6df"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="hee6_gbza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:protected-checkpoint-duotone-thin" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.hee6_gbza) {
  d: path("M9 7h6v3l-3 3 -3 -3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kysn4r6df) {
  fill: currentColor;
  d: path("M9 7h6v3l-3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

</style>
