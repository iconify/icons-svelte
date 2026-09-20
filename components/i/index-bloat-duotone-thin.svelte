<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="dvwe58bdd"/><path class="ekm49xy4p"/><path class="g7a2djb3s"/><path class="d1pwblbrj"/><path class="crv4i00bu"/><path class="wwb_9fbub"/><path class="je5qtm2zh"/><path class="g1xwr4cnp"/><path class="t2ilqxxwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-bloat-duotone-thin" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.d1pwblbrj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dvwe58bdd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ekm49xy4p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g1xwr4cnp) {
  d: path("M4 14h15");
}

:global(.g7a2djb3s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.je5qtm2zh) {
  d: path("M4 10h17");
}

:global(.t2ilqxxwv) {
  d: path("M4 18h8");
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwb_9fbub) {
  d: path("M4 6h12");
}

</style>
