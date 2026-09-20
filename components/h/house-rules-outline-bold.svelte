<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="diipsobkl"/><path class="wvn953rdk"/><path class="mvm7r4bea"/><path class="l1jjkky7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:house-rules-outline-bold" {...props}></Icon>
<style>
:global(.diipsobkl) {
  d: path("M5 3v18h14V3Z");
}

:global(.l1jjkky7x) {
  d: path("M8 18h8");
}

:global(.mvm7r4bea) {
  d: path("M8 14h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wvn953rdk) {
  d: path("M9 9V6l3 -3 3 3v3Z");
}

</style>
