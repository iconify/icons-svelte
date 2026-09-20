<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmyxx1_md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:general-device-sharp" {...props}></Icon>
<style>
:global(.hmyxx1_md) {
  fill: currentColor;
  d: path("M8.77 17V4h6.46v13zm0 2.385v-1h6.46v1z");
}

</style>
