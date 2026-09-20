<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="mw2gfo1lk"/><path class="pqt5vxabu"/><path class="z8ti_fbgk"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="ymk1v8j2l"/><path class="lyy2bnbbp"/><path class="mrbwrkdfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retrieval-eval-duotone-bold" {...props}></Icon>
<style>
:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
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

:global(.mw2gfo1lk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6.5 10 2 2L11 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.plw-owhdh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pqt5vxabu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yjc9h6oua) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymk1v8j2l) {
  d: path("m6.5 10 2 2L11 9.5");
}

:global(.z8ti_fbgk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
