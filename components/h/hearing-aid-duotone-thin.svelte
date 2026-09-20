<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qqr2y4i5k"/><path class="adp7fym0b"/><path class="movyjtqgs"/><path class="ht74g2xqg"/><path class="ph1z-dbce"/><path class="bbxz-u7vo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hearing-aid-duotone-thin" {...props}></Icon>
<style>
:global(.adp7fym0b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bbxz-u7vo) {
  d: path("M16 6a6 6 0 0 1 0 12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ht74g2xqg) {
  d: path("M6 20A6 6 0 0 1 6 8a4 4 0 0 1 6 8");
}

:global(.movyjtqgs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 6a6 6 0 0 1 0 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ph1z-dbce) {
  d: path("M16 9a3 3 0 0 1 0 6");
}

:global(.qqr2y4i5k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20A6 6 0 0 1 6 8a4 4 0 0 1 6 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
