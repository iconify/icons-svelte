<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dehnpbebl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:browser-updated-sharp" {...props}></Icon>
<style>
:global(.dehnpbebl) {
  fill: currentColor;
  d: path("M6 21v-2l1-1H2V3h10v2H4v11h16v-3h2v5h-5l1 1v2zm9-6l-5-5l1.4-1.4l2.6 2.575V3h2v8.175L18.6 8.6L20 10z");
}

</style>
