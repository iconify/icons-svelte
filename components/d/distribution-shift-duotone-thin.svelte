<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rq5svzstd"/><path class="geynzzbhp"/><path class="e6673eoyj"/><path class="mddrthmzf"/><path class="xa0iemevq"/><path class="e9i5dwbzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:distribution-shift-duotone-thin" {...props}></Icon>
<style>
:global(.e6673eoyj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10.5 13.5 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e9i5dwbzy) {
  d: path("m10.5 13.5 3 -3");
}

:global(.geynzzbhp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mddrthmzf) {
  d: path("M3 16a4 4 0 0 1 8 0");
}

:global(.rq5svzstd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa0iemevq) {
  d: path("M13 12a4 4 0 0 1 8 0");
}

</style>
