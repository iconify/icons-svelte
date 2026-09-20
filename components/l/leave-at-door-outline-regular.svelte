<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wt76_hbmn"/><path class="mp_4i_b2x"/><path class="gsl4fcakz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leave-at-door-outline-regular" {...props}></Icon>
<style>
:global(.gsl4fcakz) {
  d: path("m13.5 16 2 2 3 -3");
}

:global(.mp_4i_b2x) {
  d: path("M12 14a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wt76_hbmn) {
  d: path("M9 3H3v18h6");
}

</style>
