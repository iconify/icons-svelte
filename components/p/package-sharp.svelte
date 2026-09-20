<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyl502ght"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:package-sharp" {...props}></Icon>
<style>
:global(.iyl502ght) {
  fill: currentColor;
  d: path("M7 16.5h5v-1H7zM4 20V4h16v16zM9 5v6.962l3-1.5l3 1.5V5z");
}

</style>
