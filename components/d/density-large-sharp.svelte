<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3qifbbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:density-large-sharp" {...props}></Icon>
<style>
:global(.i3qifbbpu) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zM4 5V4h16v1z");
}

</style>
