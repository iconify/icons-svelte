<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m1sxkkbgc"/><path class="itcs4-8rc"/><path class="hvzqqmbfz"/><path class="racwnfbjp"/><path class="p33iqc74e"/><path class="et-iwmblh"/><path class="nqnw98byf"/><path class="f0qz9mbvk"/><path class="t3iybibvf"/><path class="wbz8a-gmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bed-duotone-bold" {...props}></Icon>
<style>
:global(.et-iwmblh) {
  d: path("M2 18v-7h20v7");
}

:global(.f0qz9mbvk) {
  d: path("M4 11V7h6v4");
}

:global(.hvzqqmbfz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11V7h6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.itcs4-8rc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m1sxkkbgc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18v-7h20v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.p33iqc74e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.racwnfbjp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t3iybibvf) {
  d: path("M3 18v2.5");
}

:global(.wbz8a-gmi) {
  d: path("M21 18v2.5");
}

</style>
