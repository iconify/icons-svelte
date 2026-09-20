<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="hqwqevb6s"/><path class="bu4zjnbek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mrr-outline-bold" {...props}></Icon>
<style>
:global(.bu4zjnbek) {
  d: path("M9.5 10H13");
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.hqwqevb6s) {
  d: path("M6.5 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
