<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waf4xobye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:density-small-outline" {...props}></Icon>
<style>
:global(.waf4xobye) {
  fill: currentColor;
  d: path("M3 22v-2h18v2zm0-6v-2h18v2zm0-6V8h18v2zm0-6V2h18v2z");
}

</style>
