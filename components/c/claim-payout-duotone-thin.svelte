<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcjv44b9n"/><path class="fx63l30wc"/><path class="j15uiubkt"/><path class="w-bszmb4l"/><path class="h-qjdjjlz"/><path class="nx4m-abwm"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="cji751bjl"/><path class="nweyncbfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:claim-payout-duotone-thin" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.cji751bjl) {
  d: path("M9 7.5h6");
}

:global(.fx63l30wc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-qjdjjlz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j15uiubkt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nweyncbfh) {
  d: path("M12.5 5 15 7.5 12.5 10");
}

:global(.nx4m-abwm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 5 15 7.5 12.5 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ohhz_s35v) {
  d: path("M12 12v6");
}

:global(.rcjv44b9n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t9gnp4b0n) {
  d: path("M3 12a9 9 0 0 1 18 0");
}

:global(.w-bszmb4l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yb0sj-xar) {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
