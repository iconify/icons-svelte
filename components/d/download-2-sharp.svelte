<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y60j_6bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:download-2-sharp" {...props}></Icon>
<style>
:global(.y60j_6bpn) {
  fill: currentColor;
  d: path("M5 21v-1h14v1zm6.98-3.77L6.367 9.79h3.269V3h4.711v6.789h3.27z");
}

</style>
