<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8atucppv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-horizontal-split" {...props}></Icon>
<style>
:global(.h8atucppv) {
  fill: currentColor;
  d: path("M3 19h18v-6H3zm0-8h18V9H3zm0-6v2h18V5z");
}

</style>
