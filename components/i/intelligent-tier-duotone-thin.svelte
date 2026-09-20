<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovo8937oa"/><path class="lu1q1nb0a"/><path class="tx9t6ss1e"/><path class="v1-5vcb6e"/><path class="z1422pb_r"/><path class="xx2yy-3zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:intelligent-tier-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lu1q1nb0a) {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.ovo8937oa) {
  fill: currentColor;
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tx9t6ss1e) {
  d: path("M9 2.5V5");
}

:global(.v1-5vcb6e) {
  d: path("M6.5 4.5 9 2l2.5 2.5");
}

:global(.xx2yy-3zb) {
  d: path("M12.5 19.5 15 22l2.5 -2.5");
}

:global(.z1422pb_r) {
  d: path("M15 19v2.5");
}

</style>
