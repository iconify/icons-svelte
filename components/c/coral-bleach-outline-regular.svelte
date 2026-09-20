<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bpe7e61mu"/><path class="w5v-kac9c"/><path class="og6hgh--o"/><path class="bos0j4biy"/><path class="xdkb5ybpc"/><path class="hhrer6blk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coral-bleach-outline-regular" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.bpe7e61mu) {
  d: path("M8 21v-9L5 9");
}

:global(.hhrer6blk) {
  d: path("m21 4 -5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.og6hgh--o) {
  d: path("M15 21V11l-3 -3");
}

:global(.w5v-kac9c) {
  d: path("m8 15 4 -4");
}

:global(.xdkb5ybpc) {
  d: path("m16 4 5 5");
}

</style>
