<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="art4liv1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fit-page-width-outline-sharp" {...props}></Icon>
<style>
:global(.art4liv1x) {
  fill: currentColor;
  d: path("M9 15V9l-3 3zm9-3l-3-3v6zM2 20V4h20v16zM20 6H4v12h16zM4 6v12z");
}

</style>
