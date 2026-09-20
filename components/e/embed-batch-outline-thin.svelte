<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p0mfrtbaw"/><path class="vs9x-_bah"/><path class="ll1d18k1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embed-batch-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ll1d18k1h) {
  d: path("M3 15v4h18v-4");
}

:global(.p0mfrtbaw) {
  d: path("M7.5 5 10 7.5l-4 4 -4 -4L4.5 5");
}

:global(.vs9x-_bah) {
  d: path("M19.5 5 22 7.5l-4 4 -4 -4L16.5 5");
}

</style>
