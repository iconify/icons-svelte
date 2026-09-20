<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6sl9b-sa"/><path class="t9qwmjbfp"/><path class="k7z_ogwzw"/><path class="hq_tvkb6k"/><path class="atoje4bsc"/><path class="uchchabsk"/><path class="bbj1r8bpd"/><path class="vybq366mg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:profiler-duotone-bold" {...props}></Icon>
<style>
:global(.atoje4bsc) {
  d: path("M2 6h20");
}

:global(.bbj1r8bpd) {
  d: path("M4 14h12");
}

:global(.hq_tvkb6k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6sl9b-sa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k7z_ogwzw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t9qwmjbfp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uchchabsk) {
  d: path("M2 10h14");
}

:global(.vybq366mg) {
  d: path("M4 18h6");
}

</style>
