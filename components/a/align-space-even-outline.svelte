<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-vg6ub-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-space-even-outline" {...props}></Icon>
<style>
:global(.w-vg6ub-h) {
  fill: currentColor;
  d: path("M2 4V2h20v2zm0 18v-2h20v2zm5-12V7h10v3zm0 7v-3h10v3z");
}

</style>
