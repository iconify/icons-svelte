<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="xaf7p12lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:maximize-28-filled" {...props}></Icon>
<style>
:global(.xaf7p12lo) {
  fill: currentColor;
  d: path("M3 7a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4v14a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4zm4-2a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2z");
}

</style>
