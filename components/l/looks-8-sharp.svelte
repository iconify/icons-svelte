<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkackqa9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-8-sharp" {...props}></Icon>
<style>
:global(.fkackqa9b) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm5.5-3.5h5v-4L14 12l.5-.5v-4h-5v4l.5.5l-.5.5zm1-5v-3h3v3zm0 4v-3h3v3z");
}

</style>
