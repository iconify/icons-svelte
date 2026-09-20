<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zedo2abil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:desktop-windows-sharp" {...props}></Icon>
<style>
:global(.zedo2abil) {
  fill: currentColor;
  d: path("M9 20v-1h2v-2H3V4h18v13h-8v2h2v1z");
}

</style>
