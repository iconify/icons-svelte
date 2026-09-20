<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftphci-zo"/><path class="nocp8rbgi"/><path class="ykj7ebbjl"/><path class="oqj-o0b2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cake-slice-duotone-thin" {...props}></Icon>
<style>
:global(.ftphci-zo) {
  fill: currentColor;
  d: path("M5 20v-8l6 -6h8v14Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nocp8rbgi) {
  d: path("M5 20v-8l6 -6h8v14Z");
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.ykj7ebbjl) {
  d: path("M7 10h12");
}

</style>
