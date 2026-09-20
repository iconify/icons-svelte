<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8fz6_14x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:desktop-windows-outline-sharp" {...props}></Icon>
<style>
:global(.e8fz6_14x) {
  fill: currentColor;
  d: path("M8 21v-2h2v-2H2V3h20v14h-8v2h2v2zm-4-6h16V5H4zm0 0V5z");
}

</style>
