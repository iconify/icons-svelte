<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlcaibcxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:lab-profile-outline-sharp" {...props}></Icon>
<style>
:global(.qlcaibcxi) {
  fill: currentColor;
  d: path("M8 12v-2h8v2zm0-4V6h8v2zm-2 6h8.975L18 17.95V4H6zm0 6h11.05L14 16H6zm14 2H4V2h16zM6 20V4zm0-4v-2z");
}

</style>
