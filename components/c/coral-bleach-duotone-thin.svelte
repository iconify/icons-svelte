<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tb1pycc5r"/><path class="g6ns3f45o"/><path class="ecb5qb03v"/><path class="ymhw07_9a"/><path class="kbd6zdowq"/><path class="e08jau92l"/><path class="bpe7e61mu"/><path class="w5v-kac9c"/><path class="og6hgh--o"/><path class="bos0j4biy"/><path class="xdkb5ybpc"/><path class="hhrer6blk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coral-bleach-duotone-thin" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.bpe7e61mu) {
  d: path("M8 21v-9L5 9");
}

:global(.e08jau92l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 4 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ecb5qb03v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 21V11l-3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6ns3f45o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hhrer6blk) {
  d: path("m21 4 -5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kbd6zdowq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 4 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.og6hgh--o) {
  d: path("M15 21V11l-3 -3");
}

:global(.tb1pycc5r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21v-9L5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w5v-kac9c) {
  d: path("m8 15 4 -4");
}

:global(.xdkb5ybpc) {
  d: path("m16 4 5 5");
}

:global(.ymhw07_9a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
