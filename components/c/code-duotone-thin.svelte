<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5fs0raqq"/><path class="qp_iv4crr"/><path class="onei9bb8c"/><path class="faeydrb7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-duotone-thin" {...props}></Icon>
<style>
:global(.faeydrb7z) {
  d: path("m15 6 6 6 -6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o5fs0raqq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 6 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.onei9bb8c) {
  d: path("m9 6 -6 6 6 6");
}

:global(.qp_iv4crr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 6 6 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
