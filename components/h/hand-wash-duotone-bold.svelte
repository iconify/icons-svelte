<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="syn4p7brw"/><path class="wy5f5_n8l"/><path class="pd43yny7a"/><path class="jl3jsq9eu"/><path class="qntpmnbel"/><path class="znimqt98n"/><path class="mqbr2yyal"/><path class="ehnvkinxp"/><path class="i2-ny_bzf"/><path class="rsinobb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hand-wash-duotone-bold" {...props}></Icon>
<style>
:global(.ehnvkinxp) {
  d: path("M7 4v4");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.jl3jsq9eu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mqbr2yyal) {
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
}

:global(.pd43yny7a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qntpmnbel) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rsinobb0c) {
  d: path("M17 4v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.syn4p7brw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wy5f5_n8l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.znimqt98n) {
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
}

</style>
