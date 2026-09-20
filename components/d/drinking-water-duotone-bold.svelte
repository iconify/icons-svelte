<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n0boypkyh"/><path class="xirwhd2ti"/><path class="hzi6sbb6g"/><path class="z3yxp_dum"/><path class="r182r524c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drinking-water-duotone-bold" {...props}></Icon>
<style>
:global(.hzi6sbb6g) {
  d: path("M7 5v16h10V5Z");
}

:global(.n0boypkyh) {
  fill: currentColor;
  d: path("M7 5v16h10V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xirwhd2ti) {
  fill: currentColor;
  d: path("m12 9 3 3a3 3 0 0 1 -6 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z3yxp_dum) {
  d: path("m12 9 3 3a3 3 0 0 1 -6 0Z");
}

</style>
