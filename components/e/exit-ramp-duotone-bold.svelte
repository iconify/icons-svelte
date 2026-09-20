<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xlc1jpzeg"/><path class="fml9t8nvu"/><path class="t609-3u5f"/><path class="q8-3-v_8e"/><path class="g5j0ssbtg"/><path class="fforjyb_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exit-ramp-duotone-bold" {...props}></Icon>
<style>
:global(.fforjyb_s) {
  d: path("M15.5 16H19v-3.5");
}

:global(.fml9t8nvu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h7l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g5j0ssbtg) {
  d: path("M6 10h7l6 6");
}

:global(.q8-3-v_8e) {
  d: path("M6 2v19");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t609-3u5f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 16H19v-3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xlc1jpzeg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 2v19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
