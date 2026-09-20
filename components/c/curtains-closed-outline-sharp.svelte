<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kftvxr8kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:curtains-closed-outline-sharp" {...props}></Icon>
<style>
:global(.kftvxr8kt) {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm3-1h3.75V5H6zm4.75 0h2.5V5h-2.5zm3.5 0H18V5h-3.75zM6 19V5zm12 0V5z");
}

</style>
