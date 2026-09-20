<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sb4s9qcnb"/><path class="n3z4_xsst"/><path class="v8l-dacwq"/><path class="s4e5gyxqe"/><path class="bpiqilekb"/><path class="gzq1vrb2e"/><path class="veuek9f-x"/><path class="sy50-cc1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-team-duotone-thin" {...props}></Icon>
<style>
:global(.bpiqilekb) {
  d: path("M8.5 3.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.gzq1vrb2e) {
  d: path("M18.5 3.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n3z4_xsst) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 3.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s4e5gyxqe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 13.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sb4s9qcnb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 3.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sy50-cc1z) {
  d: path("M18.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.v8l-dacwq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 13.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.veuek9f-x) {
  d: path("M8.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

</style>
