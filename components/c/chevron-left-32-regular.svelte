<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jaxzql63r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-32-regular" {...props}></Icon>
<style>
:global(.jaxzql63r) {
  fill: currentColor;
  d: path("M20.707 5.293a1 1 0 0 1 0 1.414L11.414 16l9.293 9.293a1 1 0 0 1-1.414 1.414l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0");
}

</style>
