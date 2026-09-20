<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2b8j16ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:laptop-windows-outline-sharp" {...props}></Icon>
<style>
:global(.s2b8j16ve) {
  fill: currentColor;
  d: path("M0 20v-2h4v-1H2V3h20v14h-2v1h4v2zm4-5h16V5H4zm0 0V5z");
}

</style>
