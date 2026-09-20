<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lp3etd4mx"/><path class="lh_8lcb-x"/><path class="tk9hd5usx"/><path class="s24u-_b8l"/><path class="d-_u6mtyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:claw-machine-outline-regular" {...props}></Icon>
<style>
:global(.d-_u6mtyl) {
  d: path("M14 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lh_8lcb-x) {
  d: path("M12 4v6");
}

:global(.lp3etd4mx) {
  d: path("M3 4v17h18V4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s24u-_b8l) {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.tk9hd5usx) {
  d: path("m9 13 3 -3 3 3");
}

</style>
