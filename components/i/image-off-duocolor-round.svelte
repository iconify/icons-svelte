<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ge0pu2v_p"/><path class="amvyz_4ey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-off-duocolor-round" {...props}></Icon>
<style>
:global(.amvyz_4ey) {
  d: path("M20 20c-.724.724-1.895 1-3 1H7a4 4 0 0 1-4-4V7c0-1.105.276-2.276 1-3m5-1h8a4 4 0 0 1 4 4v8");
}

:global(.ge0pu2v_p) {
  stroke-opacity: 0.4;
  d: path("m3 17l7-7m5-2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
