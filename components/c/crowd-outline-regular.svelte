<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uk0rveqaj"/><path class="ph-bhccoq"/><path class="rdx5t34om"/><path class="qynh2c4wy"/><path class="xbibi3o1e"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crowd-outline-regular" {...props}></Icon>
<style>
:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ph-bhccoq) {
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qynh2c4wy) {
  d: path("M7 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rdx5t34om) {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xbibi3o1e) {
  d: path("M13 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
