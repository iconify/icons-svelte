<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5d21vbqu"/><path class="zjhwu2bku"/><path class="f6w2936kf"/><path class="rsui_05gv"/><path class="q2i8lfb2i"/><path class="atzi6u7-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bias-check-duotone-thin" {...props}></Icon>
<style>
:global(.atzi6u7-j) {
  d: path("m14 16 3 3 5 -5");
}

:global(.f6w2936kf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 16 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5d21vbqu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q2i8lfb2i) {
  d: path("M4 13h10");
}

:global(.rsui_05gv) {
  d: path("M4 8h10");
}

:global(.zjhwu2bku) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
