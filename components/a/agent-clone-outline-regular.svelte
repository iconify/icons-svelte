<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rfpc8ubdp"/><path class="t-mha0g5h"/><path class="z0j9wnbwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-clone-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rfpc8ubdp) {
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
}

:global(.t-mha0g5h) {
  d: path("M19.19 8.37a4 4 0 1 1 -3.38 0");
}

:global(.z0j9wnbwo) {
  d: path("M4 19.5h16");
}

</style>
