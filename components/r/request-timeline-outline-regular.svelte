<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="mzkwo-z2x"/><path class="v3qgglbcl"/><path class="phup74asp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:request-timeline-outline-regular" {...props}></Icon>
<style>
:global(.lqcp5xb1v) {
  d: path("M4 3h16");
}

:global(.mzkwo-z2x) {
  d: path("M7 9.5v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phup74asp) {
  d: path("M17 9.5v5");
}

:global(.t3vzob-fn) {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

:global(.v3qgglbcl) {
  d: path("M12 9.5v5");
}

</style>
