<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p6an06b6t"/><path class="h03wmtogt"/><path class="unova7b3b"/><path class="hy6l_ib5n"/><path class="y_thay7rz"/><path class="l72iw6b2j"/><path class="tt7ypiikb"/><path class="zgod0v2rr"/><path class="du3agkbjb"/><path class="nj6hdwb2d"/><path class="olmwgycdy"/><path class="gpgtzfb8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-branch-remove-duotone-bold" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gpgtzfb8u) {
  d: path("M16.5 6.5h5");
}

:global(.h03wmtogt) {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hy6l_ib5n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l72iw6b2j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 6.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nj6hdwb2d) {
  d: path("M7 12h7.5");
}

:global(.olmwgycdy) {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.p6an06b6t) {
  fill: currentColor;
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tt7ypiikb) {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.unova7b3b) {
  fill: currentColor;
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y_thay7rz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zgod0v2rr) {
  d: path("M7 8.5v7");
}

</style>
