<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ga97lpb2d"/><path class="g_14gdcpn"/><path class="u83rpxb8q"/><path class="pdgwdvrql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:policy-list-outline-regular" {...props}></Icon>
<style>
:global(.g_14gdcpn) {
  d: path("M15 9h7");
}

:global(.ga97lpb2d) {
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pdgwdvrql) {
  d: path("M15 17h7");
}

:global(.u83rpxb8q) {
  d: path("M15 13h7");
}

</style>
