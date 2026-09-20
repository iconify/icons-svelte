<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6kztyquz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-6-sharp" {...props}></Icon>
<style>
:global(.c6kztyquz) {
  fill: currentColor;
  d: path("M11 11V9h3V7H9v10h6v-6zm0 2h2v2h-2zm-8 8V3h18v18z");
}

</style>
