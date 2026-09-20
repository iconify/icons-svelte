<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpwtlxjjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-control-key-outline" {...props}></Icon>
<style>
:global(.fpwtlxjjl) {
  fill: currentColor;
  d: path("M6.4 12.689L5.712 12L12 5.712L18.288 12l-.688.689L12 7.114z");
}

</style>
