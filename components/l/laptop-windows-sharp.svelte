<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikl58_bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:laptop-windows-sharp" {...props}></Icon>
<style>
:global(.ikl58_bwl) {
  fill: currentColor;
  d: path("M0 20v-2h4v-1H2V3h20v14h-2v1h4v2z");
}

</style>
