<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mhypmqbih"/><path class="h_cavqskd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:inverter-duocolor-sharp" {...props}></Icon>
<style>
:global(.h_cavqskd) {
  d: path("M4 3h16v18H4Zm5 14h6");
}

:global(.mhypmqbih) {
  stroke-opacity: 0.4;
  d: path("M8 11V7h8v4a5 5 0 0 1-8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
