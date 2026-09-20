<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drdne8bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:horizontal-split-outline-sharp" {...props}></Icon>
<style>
:global(.drdne8bss) {
  fill: currentColor;
  d: path("M4 18v-6h16v6zm0-8V9h16v1zm0-3V6h16v1z");
}

</style>
