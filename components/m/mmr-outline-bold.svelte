<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="w8fmvxwit"/><path class="r3-lax2ik"/><path class="fu2iodbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mmr-outline-bold" {...props}></Icon>
<style>
:global(.fu2iodbya) {
  d: path("M3 16h16");
}

:global(.r3-lax2ik) {
  d: path("m8 9 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w8fmvxwit) {
  d: path("M3 11h14");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
