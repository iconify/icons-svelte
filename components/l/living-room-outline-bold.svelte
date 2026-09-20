<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="emu6orblz"/><path class="f0mt8ybxt"/><path class="fbdov315v"/><path class="jdh6pf7zv"/><path class="tm05ptb3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:living-room-outline-bold" {...props}></Icon>
<style>
:global(.emu6orblz) {
  d: path("M2 17V9h8v8");
}

:global(.f0mt8ybxt) {
  d: path("M2 13h8");
}

:global(.fbdov315v) {
  d: path("m13 10 3 -3h3l3 3Z");
}

:global(.jdh6pf7zv) {
  d: path("M17.5 10v9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tm05ptb3a) {
  d: path("M15.5 19h4");
}

</style>
