<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8e13sbqx"/><path class="jkh8z5-ob"/><path class="d-ycm7dex"/><path class="tw1khnbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:quantize-4bit-duotone-thin" {...props}></Icon>
<style>
:global(.c8e13sbqx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 9 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d-ycm7dex) {
  d: path("m3 9 6 -6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkh8z5-ob) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h5v-5h5v-5h5V6h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tw1khnbtv) {
  d: path("M3 21h5v-5h5v-5h5V6h3");
}

</style>
