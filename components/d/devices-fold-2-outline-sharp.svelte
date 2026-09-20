<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_vkhfbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:devices-fold-2-outline-sharp" {...props}></Icon>
<style>
:global(.s_vkhfbdv) {
  fill: currentColor;
  d: path("M6.02 20V4h12.276l3.404 8.5h-3.488V20zm3.592-8.5h10.6L17.619 5H7.02zM7.018 19h10.193v-6.5H8.935L7.018 7.721zm6.597-10.75");
}

</style>
