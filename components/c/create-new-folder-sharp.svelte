<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1sdyd2_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:create-new-folder-sharp" {...props}></Icon>
<style>
:global(.p1sdyd2_h) {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm11.5-3.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
