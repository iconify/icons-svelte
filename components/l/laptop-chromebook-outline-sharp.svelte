<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xltl1rbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:laptop-chromebook-outline-sharp" {...props}></Icon>
<style>
:global(.xltl1rbef) {
  fill: currentColor;
  d: path("M0 20v-2h2V3h20v15h2v2zm10-2h4v-1h-4zm-6-3h16V5H4zm8-5");
}

</style>
