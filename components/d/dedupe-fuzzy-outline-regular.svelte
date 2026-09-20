<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="orxbg_b1j"/><path class="zuuudpbwi"/><path class="rdidnh2az"/><path class="isrkj8blm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dedupe-fuzzy-outline-regular" {...props}></Icon>
<style>
:global(.isrkj8blm) {
  d: path("M3 17h13");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.orxbg_b1j) {
  d: path("M3 4h13");
}

:global(.rdidnh2az) {
  d: path("m10 11.5 2 2 2 -2");
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
