<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="tcxfk34nj"/><path class="lzdsnnb7v"/><path class="iedujiqkb"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dense-search-outline-bold" {...props}></Icon>
<style>
:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.iedujiqkb) {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.lzdsnnb7v) {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tcxfk34nj) {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
