<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfpf-rs6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-equalizer" {...props}></Icon>
<style>
:global(.hfpf-rs6d) {
  fill: currentColor;
  d: path("M10 20h4V4h-4zm-6 0h4v-8H4zM16 9v11h4V9z");
}

</style>
