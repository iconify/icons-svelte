<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_11v4jkg"/><path class="qex7_ho4q"/><path class="j9-rqlblq"/><path class="viru9-bjc"/><path class="ymhw07_9a"/><path class="uqqniu6bc"/><path class="j2-drqnzq"/><path class="lp-jzobeh"/><path class="lvrweqtce"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:marathon-duotone-thin" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2-drqnzq) {
  d: path("m13 7 -4 4 4 4");
}

:global(.j9-rqlblq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lp-jzobeh) {
  d: path("M9 11H5");
}

:global(.lvrweqtce) {
  d: path("m13 15 4 4");
}

:global(.o_11v4jkg) {
  fill: currentColor;
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qex7_ho4q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 7 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uqqniu6bc) {
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.viru9-bjc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 15 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymhw07_9a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
