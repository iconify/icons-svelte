<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7uifmb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:menu-sharp" {...props}></Icon>
<style>
:global(.e7uifmb1n) {
  fill: currentColor;
  d: path("M3 18v-2h18v2zm0-5v-2h18v2zm0-5V6h18v2z");
}

</style>
