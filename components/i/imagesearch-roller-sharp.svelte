<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7s06dbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:imagesearch-roller-sharp" {...props}></Icon>
<style>
:global(.j7s06dbso) {
  fill: currentColor;
  d: path("M14.52 22h-4.116v-6.75h1.558v-4.5H3V4.5h2.923V3H19v4H5.923V5.5H4v4.25h8.962v5.5h1.557z");
}

</style>
