<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7nrvfbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-treemap-fill-sharp" {...props}></Icon>
<style>
:global(.m7nrvfbzk) {
  fill: currentColor;
  d: path("M9 2v20H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm2 7V2h10a1 1 0 0 1 1 1v6Zm4 13h-4V11h4Zm7-11v10a1 1 0 0 1-1 1h-4V11Z");
}

</style>
