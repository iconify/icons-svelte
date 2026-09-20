<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1_kprigi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:aod-tablet-sharp" {...props}></Icon>
<style>
:global(.e1_kprigi) {
  fill: currentColor;
  d: path("M2 19V5h20v14zm3.5-1h13V6h-13zm3-6.808v-.884h7v.884zm1 3v-.884h5v.884z");
}

</style>
