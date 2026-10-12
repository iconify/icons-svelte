<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="si_c6-wrh"/><path class="i7l0ccctm"/><path class="df185ybtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:calendar-star" {...props}></Icon>
<style>
:global(.df185ybtc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.39 13.82l.85 1.9q.14.32.49.36l2.07.22q.35.03.09.27l-1.54 1.39q-.26.24-.19.58l.43 2.03q.07.35-.23.17l-1.81-1.04q-.3-.17-.6 0l-1.81 1.04q-.3.18-.23-.17l.43-2.03q.07-.34-.19-.58l-1.54-1.39q-.26-.24.09-.27l2.07-.22q.35-.04.49-.36l.85-1.9q.14-.32.28 0");
}

:global(.i7l0ccctm) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M8 17h.01");
}

:global(.si_c6-wrh) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 20.25h-5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v3.5M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
