<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx_mfl4xu"/><path class="l7dpryp5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-star-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.bx_mfl4xu) {
  stroke-opacity: 0.4;
  d: path("m17 13.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

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

</style>
