<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylz0ybbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cellular-data-5-24-regular" {...props}></Icon>
<style>
:global(.ylz0ybbit) {
  fill: currentColor;
  d: path("M3 17.75v1.5a.75.75 0 0 0 1.5 0v-1.5a.75.75 0 0 0-1.5 0");
}

</style>
