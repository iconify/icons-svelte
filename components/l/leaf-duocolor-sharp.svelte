<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppfuhtbvd"/><path class="oqbmi0b8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:leaf-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqbmi0b8v) {
  d: path("M7 17c7 4 13-1 12-12C8 4 3 10 7 17");
}

:global(.ppfuhtbvd) {
  stroke-opacity: 0.4;
  d: path("m4 20l3-3m0 0l6-6");
}

</style>
