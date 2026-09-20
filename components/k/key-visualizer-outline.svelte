<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po936wbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:key-visualizer-outline" {...props}></Icon>
<style>
:global(.po936wbwp) {
  fill: currentColor;
  d: path("M3 21v-2h3v2zm0-4v-2h8v2zm0-4v-2h18v2zm0-4V7h8v2zm0-4V3h3v2zm5 16v-2h3v2zM8 5V3h3v2zm5 16v-2h3v2zm0-4v-2h8v2zm0-8V7h8v2zm0-4V3h3v2zm5 16v-2h3v2zm0-16V3h3v2z");
}

</style>
