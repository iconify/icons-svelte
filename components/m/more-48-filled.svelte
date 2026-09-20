<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<g class="ft5dv1b6b"><path class="gnqo1tbyt"/><path class="x3w8deb5n"/><path class="niuy-xgia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-48-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gnqo1tbyt) {
  d: path("M16.668 24a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0z");
  fill: currentColor;
}

:global(.niuy-xgia) {
  d: path("M36.168 27.5a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7z");
  fill: currentColor;
}

:global(.x3w8deb5n) {
  d: path("M28.168 24a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0z");
  fill: currentColor;
}

</style>
