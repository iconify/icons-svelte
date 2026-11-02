<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nv473kb_y"/><path class="l7dpryp5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-upload-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.l7dpryp5e) {
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nv473kb_y) {
  stroke-opacity: 0.4;
  d: path("m20 16l-3-3l-3 3m3-3v8");
}

</style>
