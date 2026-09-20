<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcjv44b9n"/><path class="fx63l30wc"/><path class="i6euqmbwt"/><path class="yu-j7jb_g"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="a6tpycbpp"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beach-trip-duotone-thin" {...props}></Icon>
<style>
:global(.a6tpycbpp) {
  d: path("M12 12v8");
}

:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.fx63l30wc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6euqmbwt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.rcjv44b9n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t9gnp4b0n) {
  d: path("M3 12a9 9 0 0 1 18 0");
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
