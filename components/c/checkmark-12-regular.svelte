<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ioa580alr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-12-regular" {...props}></Icon>
<style>
:global(.ioa580alr) {
  fill: currentColor;
  d: path("M9.854 3.146a.5.5 0 0 1 0 .708l-4.5 4.5a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.708L5 7.293l4.146-4.147a.5.5 0 0 1 .708 0");
}

</style>
