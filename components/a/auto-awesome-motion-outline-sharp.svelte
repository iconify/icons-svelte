<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4r7n9cag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:auto-awesome-motion-outline-sharp" {...props}></Icon>
<style>
:global(.w4r7n9cag) {
  fill: currentColor;
  d: path("M11 21V11h10v10zm1-1h8v-8h-8zm-5-2.77V7h10.23v1H8v9.23zm-4-4V3h10.23v1H4v9.23zM12 20v-8z");
}

</style>
