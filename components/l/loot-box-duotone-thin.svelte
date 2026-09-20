<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyq_xcb9j"/><path class="yf_brbf0s"/><path class="ms-nem7qp"/><path class="u7n9khzwg"/><path class="pdwch7bxf"/><path class="sv8lhpyik"/><path class="d8abqfbpc"/><path class="ivnzz4jio"/><path class="i9jx3nbss"/><path class="buphzhbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:loot-box-duotone-thin" {...props}></Icon>
<style>
:global(.buphzhbcx) {
  d: path("m15 9 2 -2");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9jx3nbss) {
  d: path("M9 9 7 7");
}

:global(.ivnzz4jio) {
  d: path("M12 8V5");
}

:global(.ms-nem7qp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pdwch7bxf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pyq_xcb9j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11v9h14v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sv8lhpyik) {
  d: path("M5 11v9h14v-9");
}

:global(.u7n9khzwg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yf_brbf0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
