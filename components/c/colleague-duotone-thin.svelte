<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnz9a7lxg"/><path class="tyxow4b3g"/><path class="k2jzr9u7f"/><path class="qnck32bfn"/><path class="gliukfoxr"/><path class="jjma1jbuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:colleague-duotone-thin" {...props}></Icon>
<style>
:global(.gliukfoxr) {
  d: path("M14 12v8h8v-8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jjma1jbuu) {
  d: path("M16 12V9h4v3");
}

:global(.k2jzr9u7f) {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.qnck32bfn) {
  d: path("M4 16a4 4 0 0 1 8 0");
}

:global(.tyxow4b3g) {
  fill: currentColor;
  d: path("M14 12v8h8v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wnz9a7lxg) {
  fill: currentColor;
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
