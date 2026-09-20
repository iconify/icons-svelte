<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy-9aj24e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-image-back" {...props}></Icon>
<style>
:global(.qy-9aj24e) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-1h3.75V12.5H4v-1h3.75V8.75H4v-1h16v1h-3.75v2.75H20v1h-3.75v2.75H20v1zM4 5V4h16v1z");
}

</style>
