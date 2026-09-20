<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mvm7r4bea"/><path class="jinvu3zma"/><path class="uac-t6brn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ladle-outline-bold" {...props}></Icon>
<style>
:global(.jinvu3zma) {
  d: path("M16 14a4 4 0 0 1 -8 0");
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

:global(.uac-t6brn) {
  d: path("M16 14c1 -5 -1 -10 -4 -11");
}

</style>
