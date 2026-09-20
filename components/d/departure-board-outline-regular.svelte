<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gkj6vbuly"/><path class="s-qvifbka"/><path class="h0lf65bzj"/><path class="tbfwm5oom"/><path class="l1hfmfb5f"/><path class="fvdyf6_1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:departure-board-outline-regular" {...props}></Icon>
<style>
:global(.fvdyf6_1w) {
  d: path("M5 14h4");
}

:global(.gkj6vbuly) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.h0lf65bzj) {
  d: path("M17 21v-4");
}

:global(.l1hfmfb5f) {
  d: path("M5 11h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s-qvifbka) {
  d: path("M7 21v-4");
}

:global(.tbfwm5oom) {
  d: path("M5 7h7");
}

</style>
