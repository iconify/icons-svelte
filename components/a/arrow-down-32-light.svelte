<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a6n029bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-32-light" {...props}></Icon>
<style>
:global(.a6n029bac) {
  fill: currentColor;
  d: path("M16.5 3.5a.5.5 0 0 0-1 0v23.833l-9.655-9.195a.5.5 0 0 0-.69.724l10.5 10a.5.5 0 0 0 .69 0l10.5-10a.5.5 0 0 0-.69-.724L16.5 27.333z");
}

</style>
