<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmazx7dse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-short-24-regular" {...props}></Icon>
<style>
:global(.rmazx7dse) {
  fill: currentColor;
  d: path("M11.25 4.75v14.5a.75.75 0 0 0 1.5 0V4.75a.75.75 0 0 0-1.5 0");
}

</style>
