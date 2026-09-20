<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ojk--hbsz"/><path class="hntep9b9h"/><path class="s5lnycqks"/><path class="i2-ny_bzf"/><path class="nw0y-0bem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-heater-outline-bold" {...props}></Icon>
<style>
:global(.hntep9b9h) {
  d: path("M8 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.nw0y-0bem) {
  d: path("M17 3v4");
}

:global(.ojk--hbsz) {
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s5lnycqks) {
  d: path("M7 3v4");
}

</style>
