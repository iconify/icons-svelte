<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="fkin8acuf"/><path class="f3zzxbxlm"/><path class="fyju44b5a"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="fs--blxyx"/><path class="xxenxccpt"/><path class="hlt9oudyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coverage-trend-duotone-regular" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.f3zzxbxlm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fkin8acuf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 13v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fs--blxyx) {
  d: path("M9 13v3");
}

:global(.fyju44b5a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hlt9oudyd) {
  d: path("M15 9v7");
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

:global(.wywiukbgn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xxenxccpt) {
  d: path("M12 11v5");
}

</style>
