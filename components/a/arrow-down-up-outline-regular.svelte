<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gg9qhlhxo"/><path class="v5g-gqbwm"/><path class="pa1ot6bmg"/><path class="wm_1lkfim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-up-outline-regular" {...props}></Icon>
<style>
:global(.gg9qhlhxo) {
  d: path("M8 4v16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pa1ot6bmg) {
  d: path("M16 4v16");
}

:global(.v5g-gqbwm) {
  d: path("m4 16 4 4 4 -4");
}

:global(.wm_1lkfim) {
  d: path("m12 8 4 -4 4 4");
}

</style>
