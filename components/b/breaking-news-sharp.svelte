<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie7vqfb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:breaking-news-sharp" {...props}></Icon>
<style>
:global(.ie7vqfb5w) {
  fill: currentColor;
  d: path("M6 17h2v-2H6zm0-4h2V7H6zm5 4h7v-2h-7zm0-4h7v-2h-7zm0-4h7V7h-7zM2 21V3h20v18z");
}

</style>
