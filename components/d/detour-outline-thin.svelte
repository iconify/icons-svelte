<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vhfgw5-us"/><path class="a-ogebbgz"/><path class="e2evtpg8i"/><path class="q4rhaacat"/><path class="hv2_9fjhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detour-outline-thin" {...props}></Icon>
<style>
:global(.a-ogebbgz) {
  d: path("M12 7v9");
}

:global(.e2evtpg8i) {
  d: path("M9.5 9.5 12 7l2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hv2_9fjhy) {
  d: path("m20 13 -4 4");
}

:global(.q4rhaacat) {
  d: path("m16 13 4 4");
}

:global(.vhfgw5-us) {
  d: path("M2 16h10");
}

</style>
