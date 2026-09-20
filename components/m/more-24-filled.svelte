<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<g class="ft5dv1b6b"><path class="irkn49b_k"/><path class="yjqdkbxnv"/><path class="ldgze-b-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-24-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.irkn49b_k) {
  d: path("M8.334 12a2 2 0 1 1-4 0a2 2 0 0 1 4 0z");
  fill: currentColor;
}

:global(.ldgze-b-i) {
  d: path("M18.334 14a2 2 0 1 0 0-4a2 2 0 0 0 0 4z");
  fill: currentColor;
}

:global(.yjqdkbxnv) {
  d: path("M14.334 12a2 2 0 1 1-4 0a2 2 0 0 1 4 0z");
  fill: currentColor;
}

</style>
