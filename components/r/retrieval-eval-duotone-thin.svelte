<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="pheeuwqsh"/><path class="w1y52xvec"/><path class="vad3hnt0s"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="ymk1v8j2l"/><path class="lyy2bnbbp"/><path class="mrbwrkdfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retrieval-eval-duotone-thin" {...props}></Icon>
<style>
:global(.dba5rjonf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.lyy2bnbbp) {
  d: path("m10 7 4 4");
}

:global(.mrbwrkdfc) {
  d: path("m14 7 -4 4");
}

:global(.pheeuwqsh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6.5 10 2 2L11 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vad3hnt0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w1y52xvec) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymk1v8j2l) {
  d: path("m6.5 10 2 2L11 9.5");
}

:global(.zl5hlnbpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
