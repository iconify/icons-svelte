<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xing1zb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-off-sharp" {...props}></Icon>
<style>
:global(.xing1zb8b) {
  fill: currentColor;
  d: path("M22 19.175L6.85 4H9.7l2 2H22zM20.475 23.3l-3.3-3.3H2V4h2l2 2H3.2L.7 3.5l1.4-1.4l19.8 19.8z");
}

</style>
