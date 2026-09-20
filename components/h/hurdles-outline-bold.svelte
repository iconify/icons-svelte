<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vhnbtvbtn"/><path class="pb147jbda"/><path class="wfoy3xxos"/><path class="dznv025mt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hurdles-outline-bold" {...props}></Icon>
<style>
:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.pb147jbda) {
  d: path("M6 8v12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.wfoy3xxos) {
  d: path("M18 8v12");
}

</style>
