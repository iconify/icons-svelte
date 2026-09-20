<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ehzfylb8o"/><path class="e4lpx1jcu"/><path class="okud9xj_d"/><path class="eq1nrcbpl"/><path class="w2atjyb_m"/><path class="ey3upmocl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:organ-donor-duotone-bold" {...props}></Icon>
<style>
:global(.e4lpx1jcu) {
  fill: currentColor;
  d: path("M4 11a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ehzfylb8o) {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.eq1nrcbpl) {
  d: path("M4 11a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
}

:global(.ey3upmocl) {
  d: path("M14 14h4");
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w2atjyb_m) {
  d: path("M14 10h6");
}

</style>
