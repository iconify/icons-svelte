<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="baerff2wm"/><path class="pmhsn037r"/><path class="qr1iqpomq"/><path class="zm2dyvb-o"/><path class="tkgsjrp5m"/><path class="i1uqf7jtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lineage-column-outline-bold" {...props}></Icon>
<style>
:global(.baerff2wm) {
  d: path("M2 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.i1uqf7jtv) {
  d: path("M17.5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pmhsn037r) {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.qr1iqpomq) {
  d: path("M9 8h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tkgsjrp5m) {
  d: path("M4.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
