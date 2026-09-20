<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu3xiy_iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:create-new-folder-sharp" {...props}></Icon>
<style>
:global(.eu3xiy_iw) {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm12-4h2v-2h2v-2h-2v-2h-2v2h-2v2h2z");
}

</style>
