<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p37-48m8n"/><path class="lfdcifmie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cog-railway-duocolor-sharp" {...props}></Icon>
<style>
:global(.lfdcifmie) {
  d: path("M6 19V7h5V4h7v9zm0-7h5V9h7m-7-2v2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p37-48m8n) {
  stroke-opacity: 0.4;
  d: path("m4 20l16-8M6 19l1 2m3-4l1 2m3-4l1 2m3-4l1 2");
}

</style>
