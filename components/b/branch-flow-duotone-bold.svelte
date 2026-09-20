<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t2gh3_3yj"/><path class="m4ozbdcmd"/><path class="uol1biies"/><path class="q9br621tu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:branch-flow-duotone-bold" {...props}></Icon>
<style>
:global(.m4ozbdcmd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 12 5 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q9br621tu) {
  d: path("m9 12 5 5h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t2gh3_3yj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h7l5 -5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uol1biies) {
  d: path("M2 12h7l5 -5h8");
}

</style>
