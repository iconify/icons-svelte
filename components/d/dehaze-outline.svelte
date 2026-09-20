<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_7kbwyeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dehaze-outline" {...props}></Icon>
<style>
:global(.e_7kbwyeh) {
  fill: currentColor;
  d: path("M3 7V5h18v2zm0 12v-2h18v2zm0-6v-2h18v2z");
}

</style>
