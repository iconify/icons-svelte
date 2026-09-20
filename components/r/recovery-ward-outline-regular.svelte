<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t3v74kb6y"/><path class="dezc-zb_n"/><path class="om3l78bic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recovery-ward-outline-regular" {...props}></Icon>
<style>
:global(.dezc-zb_n) {
  d: path("M2 16.5h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.om3l78bic) {
  d: path("M8 6a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
}

:global(.t3v74kb6y) {
  d: path("M2 20v-7h20v7");
}

</style>
