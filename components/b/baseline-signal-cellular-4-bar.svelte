<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_cyzplpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-signal-cellular-4-bar" {...props}></Icon>
<style>
:global(.g_cyzplpb) {
  fill: currentColor;
  d: path("M2 22h20V2z");
}

</style>
