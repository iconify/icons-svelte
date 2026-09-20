<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vpv504bbj"/><path class="st4jvibbh"/><path class="v-v1vx84b"/><path class="xpjur0b_h"/><path class="amujw3_wp"/><path class="lf67ljb6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backup-tier-duotone-regular" {...props}></Icon>
<style>
:global(.amujw3_wp) {
  d: path("m9.5 13 2.5 2.5 2.5 -2.5");
}

:global(.lf67ljb6v) {
  d: path("M4 19.25A2.25 2.25 0 0 1 6.25 17h11.5A2.25 2.25 0 0 1 20 19.25a2.25 2.25 0 0 1 -2.25 2.25H6.25A2.25 2.25 0 0 1 4 19.25");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.st4jvibbh) {
  fill: currentColor;
  d: path("M4 19.25A2.25 2.25 0 0 1 6.25 17h11.5A2.25 2.25 0 0 1 20 19.25a2.25 2.25 0 0 1 -2.25 2.25H6.25A2.25 2.25 0 0 1 4 19.25");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v-v1vx84b) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.vpv504bbj) {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xpjur0b_h) {
  d: path("M12 11.5V14");
}

</style>
