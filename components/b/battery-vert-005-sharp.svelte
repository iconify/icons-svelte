<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugfs2wb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-vert-005-sharp" {...props}></Icon>
<style>
:global(.ugfs2wb9x) {
  fill: currentColor;
  d: path("M9 19h6V6H9v13Zm-2 3V4h3V2h4v2h3v18H7Z");
}

</style>
