<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2v7_fg2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-align-justify-sharp" {...props}></Icon>
<style>
:global(.p2v7_fg2s) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-1h16v1zm0-3.75v-1h16v1zm0-3.75v-1h16v1zM4 5V4h16v1z");
}

</style>
