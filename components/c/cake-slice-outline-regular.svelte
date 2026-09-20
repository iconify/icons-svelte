<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nocp8rbgi"/><path class="ykj7ebbjl"/><path class="oqj-o0b2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cake-slice-outline-regular" {...props}></Icon>
<style>
:global(.nocp8rbgi) {
  d: path("M5 20v-8l6 -6h8v14Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.ykj7ebbjl) {
  d: path("M7 10h12");
}

</style>
