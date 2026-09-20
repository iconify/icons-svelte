<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhreoxb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:density-medium-outline" {...props}></Icon>
<style>
:global(.yhreoxb4k) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-7.5v-1h16v1zM4 5V4h16v1z");
}

</style>
