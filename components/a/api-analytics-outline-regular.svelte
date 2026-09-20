<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n09nomjwg"/><path class="tzv123bil"/><path class="wrji4lgnj"/><path class="gjmq94baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:api-analytics-outline-regular" {...props}></Icon>
<style>
:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.n09nomjwg) {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tzv123bil) {
  d: path("M9 10v5");
}

:global(.wrji4lgnj) {
  d: path("M12 8v7");
}

</style>
