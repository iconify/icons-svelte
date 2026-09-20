<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kf3k8pbxe"/><path class="tdrtjkcws"/><path class="w-xoojbyn"/><path class="np0d7gb6n"/><path class="atoje4bsc"/><path class="uchchabsk"/><path class="bbj1r8bpd"/><path class="vybq366mg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:profiler-duotone-regular" {...props}></Icon>
<style>
:global(.atoje4bsc) {
  d: path("M2 6h20");
}

:global(.bbj1r8bpd) {
  d: path("M4 14h12");
}

:global(.kf3k8pbxe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.np0d7gb6n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tdrtjkcws) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uchchabsk) {
  d: path("M2 10h14");
}

:global(.vybq366mg) {
  d: path("M4 18h6");
}

:global(.w-xoojbyn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
