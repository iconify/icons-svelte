<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="m0ltc1ukh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:block-16-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.m0ltc1ukh) {
  d: path("M8 2a6 6 0 1 1 0 12A6 6 0 0 1 8 2zm2.502 5.5H5.5a.5.5 0 0 0 0 1h5.002a.5.5 0 1 0 0-1z");
  fill: currentColor;
}

</style>
