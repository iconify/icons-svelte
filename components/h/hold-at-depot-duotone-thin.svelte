<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwi87ac4g"/><path class="bm7onkbce"/><path class="rweggx0cr"/><path class="e77gki8ci"/><path class="n92b0ebji"/><path class="m7aa3ibix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hold-at-depot-duotone-thin" {...props}></Icon>
<style>
:global(.bm7onkbce) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e77gki8ci) {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m7aa3ibix) {
  d: path("M14.5 11v6");
}

:global(.n92b0ebji) {
  d: path("M9.5 11v6");
}

:global(.nwi87ac4g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rweggx0cr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
