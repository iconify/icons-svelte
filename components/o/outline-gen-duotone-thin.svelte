<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="rar1qabjk"/><path class="tzn5wr-vc"/><path class="vbouf8bpc"/><path class="k6nj2fbya"/><path class="r1-ktgx-e"/><path class="nmmozg1gr"/><path class="t33f_gbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:outline-gen-duotone-thin" {...props}></Icon>
<style>
:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.nmmozg1gr) {
  d: path("M7 15h14");
}

:global(.r1-ktgx-e) {
  d: path("M7 10h14");
}

:global(.rar1qabjk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t33f_gbzo) {
  d: path("M11 20h10");
}

:global(.tzn5wr-vc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vbouf8bpc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
