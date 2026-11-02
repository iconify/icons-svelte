<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruc7hnxun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-fill-sharp" {...props}></Icon>
<style>
:global(.ruc7hnxun) {
  fill: currentColor;
  d: path("M3 17V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m12 2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
