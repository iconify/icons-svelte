<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d-ycm7dex"/><path class="tw1khnbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:quantize-4bit-outline-bold" {...props}></Icon>
<style>
:global(.d-ycm7dex) {
  d: path("m3 9 6 -6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tw1khnbtv) {
  d: path("M3 21h5v-5h5v-5h5V6h3");
}

</style>
