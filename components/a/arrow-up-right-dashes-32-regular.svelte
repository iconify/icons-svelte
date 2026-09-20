<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nc4fydjit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-right-dashes-32-regular" {...props}></Icon>
<style>
:global(.nc4fydjit) {
  fill: currentColor;
  d: path("M15 3a1 1 0 1 0 0 2h10.586l-5.293 5.293a1 1 0 0 0 1.414 1.414L27 6.414V17a1 1 0 1 0 2 0V4a1 1 0 0 0-1-1zm-3.793 19.207a1 1 0 0 0-1.414-1.414l-6.5 6.5a1 1 0 1 0 1.414 1.414zm8-9.414a1 1 0 0 1 0 1.414l-5.5 5.5a1 1 0 0 1-1.414-1.414l5.5-5.5a1 1 0 0 1 1.414 0");
}

</style>
