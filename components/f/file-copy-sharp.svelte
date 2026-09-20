<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wptt8kbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:file-copy-sharp" {...props}></Icon>
<style>
:global(.wptt8kbso) {
  fill: currentColor;
  d: path("M6 19V1h9l6 6v12zm8-11h5l-5-5zM2 23V7h2v14h11v2z");
}

</style>
