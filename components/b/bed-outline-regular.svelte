<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="et-iwmblh"/><path class="nqnw98byf"/><path class="f0qz9mbvk"/><path class="t3iybibvf"/><path class="wbz8a-gmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bed-outline-regular" {...props}></Icon>
<style>
:global(.et-iwmblh) {
  d: path("M2 18v-7h20v7");
}

:global(.f0qz9mbvk) {
  d: path("M4 11V7h6v4");
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t3iybibvf) {
  d: path("M3 18v2.5");
}

:global(.wbz8a-gmi) {
  d: path("M21 18v2.5");
}

</style>
