<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jirei-bba"/><path class="sfh31bcxq"/><path class="nzu-xuz8n"/><path class="qfaf8otig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:printer-outline-regular" {...props}></Icon>
<style>
:global(.jirei-bba) {
  d: path("M7 6.5V2h10v4.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzu-xuz8n) {
  d: path("M4.5 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qfaf8otig) {
  d: path("M7 18v4h10v-4");
}

:global(.sfh31bcxq) {
  d: path("M2 10.5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
