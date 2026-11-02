<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_vk2bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-horizontal-bulk" {...props}></Icon>
<style>
:global(.ox_vk2bqq) {
  fill: currentColor;
  d: path("M4.158 11.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
