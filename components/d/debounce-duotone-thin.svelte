<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfy_enbzb"/><path class="uuxi52b8u"/><path class="lezox35rc"/><path class="xz6bf05cf"/><path class="sxll69axz"/><path class="zitzxjbtk"/><path class="h26bvabki"/><path class="e8mk-vdvn"/><path class="y5k8b5bfa"/><path class="wskxlyzso"/><path class="tuynf1bdi"/><path class="mhila7bcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:debounce-duotone-thin" {...props}></Icon>
<style>
:global(.e8mk-vdvn) {
  d: path("M6 9v6");
}

:global(.h26bvabki) {
  d: path("M3 9v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lezox35rc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mhila7bcl) {
  d: path("M20 7v10");
}

:global(.rfy_enbzb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sxll69axz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tuynf1bdi) {
  d: path("m15 10 2 2 -2 2");
}

:global(.uuxi52b8u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wskxlyzso) {
  d: path("M12 12h3");
}

:global(.xz6bf05cf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y5k8b5bfa) {
  d: path("M9 9v6");
}

:global(.zitzxjbtk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
