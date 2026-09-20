<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_970ccbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-align-right-outline-sharp" {...props}></Icon>
<style>
:global(.g_970ccbu) {
  fill: currentColor;
  d: path("M4 5V4h16v1zm6 3.75v-1h10v1zM4 12.5v-1h16v1zm6 3.75v-1h10v1zM4 20v-1h16v1z");
}

</style>
