<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="taxw3hecl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dark-theme-20-filled" {...props}></Icon>
<style>
:global(.taxw3hecl) {
  fill: currentColor;
  d: path("M10 3.5a6.5 6.5 0 1 1 0 13zM10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
