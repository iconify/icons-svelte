<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ac2e6i0cq"/><path class="ogeh55o6v"/><path class="uol1biies"/><path class="q9br621tu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:branch-flow-duotone-thin" {...props}></Icon>
<style>
:global(.ac2e6i0cq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h7l5 -5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ogeh55o6v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 5 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q9br621tu) {
  d: path("m9 12 5 5h8");
}

:global(.uol1biies) {
  d: path("M2 12h7l5 -5h8");
}

</style>
