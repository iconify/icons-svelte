<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0ugme01d"/><path class="j2rh_abzz"/><path class="lo13e1bkv"/><path class="x212dunwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cruise-ship-outline-bold" {...props}></Icon>
<style>
:global(.j2rh_abzz) {
  d: path("M5 15v-4h14v4");
}

:global(.lo13e1bkv) {
  d: path("M9 11V7h7v4");
}

:global(.r0ugme01d) {
  d: path("M2 15h20l-5 5H7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x212dunwb) {
  d: path("M11 7V3h3v4");
}

</style>
