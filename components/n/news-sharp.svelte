<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue_vhvbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:news-sharp" {...props}></Icon>
<style>
:global(.ue_vhvbsw) {
  fill: currentColor;
  d: path("M3 21V3h13l5 5v13zM15 5v4h4zM7 17h10v-2H7zm0-8h5V7H7zm0 4h10v-2H7z");
}

</style>
