<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kj_xiu02e"/><path class="zwbbmtbru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-radar-outline-bold" {...props}></Icon>
<style>
:global(.kj_xiu02e) {
  d: path("m12 4 8 8 -8 8 -8 -8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zwbbmtbru) {
  d: path("m12 8 4 4 -4 4 -4 -4Z");
}

</style>
