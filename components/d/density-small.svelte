<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csb4zpv7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:density-small" {...props}></Icon>
<style>
:global(.csb4zpv7z) {
  fill: currentColor;
  d: path("M4 21v-1h16v1zm0-5.5v-1h16v1zm0-6v-1h16v1zM4 4V3h16v1z");
}

</style>
