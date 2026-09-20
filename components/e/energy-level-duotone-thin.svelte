<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0eu_912v"/><path class="nzfvycb-k"/><path class="r182r524c"/><path class="c7z9o8buo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:energy-level-duotone-thin" {...props}></Icon>
<style>
:global(.c7z9o8buo) {
  d: path("M7 15h10");
}

:global(.f0eu_912v) {
  fill: currentColor;
  d: path("M7 4h10v17H7Z");
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

:global(.nzfvycb-k) {
  d: path("M7 4h10v17H7Z");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

</style>
