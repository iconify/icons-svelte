<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv1m3q_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-footer-sharp" {...props}></Icon>
<style>
:global(.kyv1m3q_x) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V3h18v14z");
}

</style>
