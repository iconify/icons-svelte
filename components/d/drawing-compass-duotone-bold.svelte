<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jpcl7o5sc"/><path class="eod8g3uqm"/><path class="l0ljkkb4b"/><path class="ht9zq9bpv"/><path class="fnf6pdbdu"/><path class="xwissob6k"/><path class="d4f9j2bku"/><path class="x1_r36phd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drawing-compass-duotone-bold" {...props}></Icon>
<style>
:global(.d4f9j2bku) {
  d: path("m12 9 6 6v4");
}

:global(.eod8g3uqm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 9 -6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fnf6pdbdu) {
  d: path("M12 3v6");
}

:global(.ht9zq9bpv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jpcl7o5sc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l0ljkkb4b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 9 6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.xwissob6k) {
  d: path("m12 9 -6 6v4");
}

</style>
