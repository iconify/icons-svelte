<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="onu1akn2n"/><path class="u91se6bfv"/><path class="qj7jubcuz"/><path class="qlf-7wwqa"/><path class="vh99xel1e"/><path class="vhfgw5-us"/><path class="a-ogebbgz"/><path class="e2evtpg8i"/><path class="q4rhaacat"/><path class="hv2_9fjhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detour-duotone-bold" {...props}></Icon>
<style>
:global(.a-ogebbgz) {
  d: path("M12 7v9");
}

:global(.e2evtpg8i) {
  d: path("M9.5 9.5 12 7l2.5 2.5");
}

:global(.hv2_9fjhy) {
  d: path("m20 13 -4 4");
}

:global(.onu1akn2n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q4rhaacat) {
  d: path("m16 13 4 4");
}

:global(.qj7jubcuz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 9.5 12 7l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qlf-7wwqa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 13 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u91se6bfv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vh99xel1e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 13 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhfgw5-us) {
  d: path("M2 16h10");
}

</style>
