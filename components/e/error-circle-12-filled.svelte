<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z4493jbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:error-circle-12-filled" {...props}></Icon>
<style>
:global(.z4493jbtx) {
  fill: currentColor;
  d: path("M6 11A5 5 0 1 0 6 1a5 5 0 0 0 0 10m-.75-2.75a.75.75 0 1 1 1.5 0a.75.75 0 0 1-1.5 0m.258-4.84a.5.5 0 0 1 .984 0l.008.09V6l-.008.09a.5.5 0 0 1-.984 0L5.5 6V3.5z");
}

</style>
