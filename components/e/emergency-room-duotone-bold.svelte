<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dnmgxtb7v"/><path class="jycpvgb1i"/><path class="qpuuxkb2r"/><path class="cfwhgr43a"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:emergency-room-duotone-bold" {...props}></Icon>
<style>
:global(.cfwhgr43a) {
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
}

:global(.dnmgxtb7v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jycpvgb1i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qpuuxkb2r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>
