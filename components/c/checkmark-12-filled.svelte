<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mwv61nial"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-12-filled" {...props}></Icon>
<style>
:global(.mwv61nial) {
  fill: currentColor;
  d: path("M9.765 3.205a.75.75 0 0 1 .03 1.06l-4.25 4.5a.75.75 0 0 1-1.075.015L2.22 6.53a.75.75 0 0 1 1.06-1.06l1.705 1.704l3.72-3.939a.75.75 0 0 1 1.06-.03");
}

</style>
