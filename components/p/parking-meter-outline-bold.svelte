<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kacaq8-ee"/><path class="o2i86qb_j"/><path class="uadefenvd"/><path class="qr1iqpomq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parking-meter-outline-bold" {...props}></Icon>
<style>
:global(.kacaq8-ee) {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.o2i86qb_j) {
  d: path("M12 14v8");
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

:global(.uadefenvd) {
  d: path("M7 22h10");
}

</style>
