<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzt9ch-wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:maximize" {...props}></Icon>
<style>
:global(.yzt9ch-wm) {
  fill: currentColor;
  d: path("M5 5V4h14v1z");
}

</style>
