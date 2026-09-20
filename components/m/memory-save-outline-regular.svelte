<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pv9xj1b7g"/><path class="gzf8q_b5i"/><path class="x7gyblbnl"/><path class="i33dqh0th"/><path class="czv374byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-save-outline-regular" {...props}></Icon>
<style>
:global(.czv374byt) {
  d: path("M10 16h11");
}

:global(.gzf8q_b5i) {
  d: path("m5 9 2 2 -2 2");
}

:global(.i33dqh0th) {
  d: path("M10 11h11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pv9xj1b7g) {
  d: path("M2 11h5");
}

:global(.x7gyblbnl) {
  d: path("M10 6h11");
}

</style>
