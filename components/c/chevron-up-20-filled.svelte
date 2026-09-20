<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t0-e6rzsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-up-20-filled" {...props}></Icon>
<style>
:global(.t0-e6rzsc) {
  fill: currentColor;
  d: path("M4.207 12.267a.75.75 0 0 1 .026-1.06l5.25-5.002a.75.75 0 0 1 1.035 0l5.25 5.001a.75.75 0 0 1-1.034 1.086L10 7.784l-4.734 4.508a.75.75 0 0 1-1.06-.025");
}

</style>
