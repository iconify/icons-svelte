<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cqa5wmi5c"/><path class="mf1x1ebvc"/><path class="mwec8jblq"/><path class="tp3wfdbxm"/><path class="tqteed1fm"/><path class="hqkel0bnd"/><path class="uaurn5bqf"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:canyon-duotone-bold" {...props}></Icon>
<style>
:global(.cqa5wmi5c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 3h6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hqkel0bnd) {
  d: path("M22 3h-6v18");
}

:global(.mf1x1ebvc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M22 3h-6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mwec8jblq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tp3wfdbxm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tqteed1fm) {
  d: path("M2 3h6v18");
}

:global(.uaurn5bqf) {
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
}

</style>
