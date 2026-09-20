<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iqi_aabed"/><path class="xgrfb-bqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:regularise-outline-bold" {...props}></Icon>
<style>
:global(.iqi_aabed) {
  d: path("m3 15 5 -5 5 5 5 -5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
