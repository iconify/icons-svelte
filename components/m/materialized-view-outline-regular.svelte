<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="te6wlfhwg"/><path class="hb0ic8bmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:materialized-view-outline-regular" {...props}></Icon>
<style>
:global(.hb0ic8bmn) {
  d: path("M7 9a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.te6wlfhwg) {
  d: path("M2 5a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
