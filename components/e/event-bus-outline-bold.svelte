<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x26a8iq1c"/><path class="ugztwkaee"/><path class="j-bg0m85s"/><path class="th8j40bfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-bus-outline-bold" {...props}></Icon>
<style>
:global(.j-bg0m85s) {
  d: path("M12 14.5V19");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.th8j40bfn) {
  d: path("M18 5v4.5");
}

:global(.ugztwkaee) {
  d: path("M6 5v4.5");
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

</style>
