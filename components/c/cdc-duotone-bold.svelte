<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="siqrysbwb"/><path class="pquf1ccxc"/><path class="bonttq6md"/><path class="i55cujbki"/><path class="etqzyebuj"/><path class="yaetm9cyz"/><path class="wn519caci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cdc-duotone-bold" {...props}></Icon>
<style>
:global(.bonttq6md) {
  d: path("M2 9h8");
}

:global(.etqzyebuj) {
  d: path("M13 12h2.5");
}

:global(.i55cujbki) {
  d: path("M2 14h8");
}

:global(.pquf1ccxc) {
  d: path("M2 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.siqrysbwb) {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wn519caci) {
  d: path("m19 9 3 3 -3 3");
}

:global(.yaetm9cyz) {
  d: path("M18 12h2.5");
}

</style>
