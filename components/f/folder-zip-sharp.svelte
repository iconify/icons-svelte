<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hinnpcz4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:folder-zip-sharp" {...props}></Icon>
<style>
:global(.hinnpcz4o) {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm11-1h2v-2h2v-2h-2v-2h2v-2h-2V8h-2v2h2v2h-2v2h2v2h-2z");
}

</style>
