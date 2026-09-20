<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr87vet0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:horizontal-split-outline-sharp" {...props}></Icon>
<style>
:global(.dr87vet0p) {
  fill: currentColor;
  d: path("M3 19v-6h18v6zm0-8V9h18v2zm0-4V5h18v2z");
}

</style>
