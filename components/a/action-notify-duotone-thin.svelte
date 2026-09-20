<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezg__mbcy"/><path class="uxwbq-n4s"/><path class="shq6z05au"/><path class="vvumupblr"/><path class="gnqb99ipa"/><path class="tp8vjxbvr"/><path class="m_812vyum"/><path class="qml-hybqn"/><path class="u4sowhi7h"/><path class="if5ft31dv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:action-notify-duotone-thin" {...props}></Icon>
<style>
:global(.ezg__mbcy) {
  fill: currentColor;
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gnqb99ipa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.m_812vyum) {
  d: path("M6 12v4");
}

:global(.qml-hybqn) {
  d: path("M18 12v4");
}

:global(.shq6z05au) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tp8vjxbvr) {
  d: path("M6 12a6 6 0 0 1 12 0");
}

:global(.u4sowhi7h) {
  d: path("M4 16h16");
}

:global(.uxwbq-n4s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vvumupblr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
