<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="xg3yyebvz"/><path class="wdpreqbqj"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="d7edxnn1x"/><path class="s00zhtbiw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:query-decompose-duotone-regular" {...props}></Icon>
<style>
:global(.d7edxnn1x) {
  d: path("M5.5 10H8l2.5 -2.5H13");
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qa-jr78us) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s00zhtbiw) {
  d: path("m8 10 2.5 2.5H13");
}

:global(.vxtvt1e5w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wdpreqbqj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 10 2.5 2.5H13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xg3yyebvz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 10H8l2.5 -2.5H13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
