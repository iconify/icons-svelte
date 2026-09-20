<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="e2h8frb7a"/><path class="qbcupf2rr"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="ns_05qbai"/><path class="zm2dyvb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baseline-approve-duotone-regular" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.e2h8frb7a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 11 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ku_telleq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ns_05qbai) {
  d: path("m9 11 2 2 4 -4");
}

:global(.qbcupf2rr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wywiukbgn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
