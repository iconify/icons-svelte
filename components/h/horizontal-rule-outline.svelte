<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvqx3mvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:horizontal-rule-outline" {...props}></Icon>
<style>
:global(.wvqx3mvqo) {
  fill: currentColor;
  d: path("M5 12.5v-1h14v1z");
}

</style>
