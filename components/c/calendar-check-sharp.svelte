<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb2oqdfvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:calendar-check-sharp" {...props}></Icon>
<style>
:global(.tb2oqdfvz) {
  fill: currentColor;
  d: path("M3 22V4h3V2h2v2h8V2h2v2h3v8.375l-2 2V10H5v10h6.2l2 2zm13.55.5L13 18.95l1.4-1.4l2.125 2.125l4.25-4.25l1.4 1.425z");
}

</style>
