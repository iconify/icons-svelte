<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_9v_pbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-navigation-sharp" {...props}></Icon>
<style>
:global(.q_9v_pbxm) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-4.615h14V5H5z");
}

</style>
