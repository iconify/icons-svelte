<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypbo53bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:equal-outline" {...props}></Icon>
<style>
:global(.ypbo53bfx) {
  fill: currentColor;
  d: path("M5 16v-2h14v2zm0-6V8h14v2z");
}

</style>
