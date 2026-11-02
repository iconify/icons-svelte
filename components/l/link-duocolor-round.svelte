<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hw_dngr3f"/><path class="w00z3jbhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-duocolor-round" {...props}></Icon>
<style>
:global(.hw_dngr3f) {
  stroke-opacity: 0.4;
  d: path("m8 16l8-8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w00z3jbhb) {
  d: path("m7 11l-2 2a4.243 4.243 0 0 0 6 6l2-2m4-4l2-2a4.243 4.243 0 0 0-6-6l-2 2");
}

</style>
