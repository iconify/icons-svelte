<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="bt_2bvgpa"/><path class="tlaolnbzt"/><path class="vwmqidksx"/><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="flq2w3bwj"/><path class="k5f0ncbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cross-attention-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.flq2w3bwj) {
  d: path("m9.5 9.5 5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k5f0ncbhf) {
  d: path("m14.5 9.5 -5 5");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.tlaolnbzt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 9.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vwmqidksx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14.5 9.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
