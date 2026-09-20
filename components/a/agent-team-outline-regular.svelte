<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bpiqilekb"/><path class="gzq1vrb2e"/><path class="veuek9f-x"/><path class="sy50-cc1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-team-outline-regular" {...props}></Icon>
<style>
:global(.bpiqilekb) {
  d: path("M8.5 3.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.gzq1vrb2e) {
  d: path("M18.5 3.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sy50-cc1z) {
  d: path("M18.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.veuek9f-x) {
  d: path("M8.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

</style>
