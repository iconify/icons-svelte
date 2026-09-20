<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p8a7rmkzk"/><path class="eev_c9mlp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-down-up-outline-regular" {...props}></Icon>
<style>
:global(.eev_c9mlp) {
  d: path("m7 20 5 -5 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p8a7rmkzk) {
  d: path("m7 4 5 5 5 -5");
}

</style>
