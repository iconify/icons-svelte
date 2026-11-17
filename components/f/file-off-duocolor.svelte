<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zo-v9hbio"/><path class="s4l6akbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-off-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s4l6akbcl) {
  d: path("M13 3H7M5 7v12a2 2 0 0 0 2 2h10c.552 0 1.052-.224 1.414-.586M19 15V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

:global(.zo-v9hbio) {
  stroke-opacity: 0.4;
  d: path("m2 4l18 18");
}

</style>
