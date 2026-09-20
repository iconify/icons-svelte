<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="z915upbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:door-28-filled" {...props}></Icon>
<style>
:global(.z915upbpa) {
  fill: currentColor;
  d: path("M8 2a3 3 0 0 0-3 3v18a3 3 0 0 0 3 3h12a3 3 0 0 0 3-3V5a3 3 0 0 0-3-3zm1.5 13a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
