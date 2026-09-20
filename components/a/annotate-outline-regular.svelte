<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="btdmtu_xg"/><path class="zaehmnb6i"/><path class="wg8_ddc1f"/><path class="t9z-q_-wf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:annotate-outline-regular" {...props}></Icon>
<style>
:global(.btdmtu_xg) {
  d: path("M14 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t9z-q_-wf) {
  d: path("m15 16 4 -4 2 2 -4 4Z");
}

:global(.wg8_ddc1f) {
  d: path("M6 12h6");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.zaehmnb6i) {
  d: path("M6 8h6");
}

</style>
