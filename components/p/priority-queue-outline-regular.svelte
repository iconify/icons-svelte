<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zuuudpbwi"/><path class="kh31pt5af"/><path class="t99bgtbzx"/><path class="ecismzb4h"/><path class="mo-r4ib5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:priority-queue-outline-regular" {...props}></Icon>
<style>
:global(.ecismzb4h) {
  d: path("M20 15V9");
}

:global(.kh31pt5af) {
  d: path("M3 13h14");
}

:global(.mo-r4ib5t) {
  d: path("m18 11 2 -2 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t99bgtbzx) {
  d: path("M3 18h14");
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
