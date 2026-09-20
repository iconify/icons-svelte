<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzwbs2bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:right-panel-open-outline-sharp" {...props}></Icon>
<style>
:global(.qzwbs2bus) {
  fill: currentColor;
  d: path("M11.5 16V8l-4 4zm4.5 3h3V5h-3zM5 19h9V5H5zm11 0h3zM3 21V3h18v18z");
}

</style>
