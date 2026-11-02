<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d8olgobtu"/><path class="tw0dguk3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:label-duotone-sharp" {...props}></Icon>
<style>
:global(.d8olgobtu) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6h5l6 6l-6 6H4V6Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.tw0dguk3u) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6h5l6 6l-6 6H4V6z");
}

</style>
