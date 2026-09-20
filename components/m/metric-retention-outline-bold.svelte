<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f73i47bnv"/><path class="uzmclv6tb"/><path class="mke92-oua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metric-retention-outline-bold" {...props}></Icon>
<style>
:global(.f73i47bnv) {
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.mke92-oua) {
  d: path("M12 11h2.5");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uzmclv6tb) {
  d: path("M12 8v3");
}

</style>
