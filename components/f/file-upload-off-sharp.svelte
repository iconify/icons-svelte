<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz-c02buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:file-upload-off-sharp" {...props}></Icon>
<style>
:global(.oz-c02buf) {
  fill: currentColor;
  d: path("m12 4l5 5l-1.4 1.45l-2.6-2.6v2.3l-2-2l-1.575-1.575zm-1 12v-5l2 2v3zm8.775 6.625L17.15 20H4v-5h2v3h9.15L1.375 4.225L2.8 2.8l18.4 18.4zM20 17.15l-2-2V15h2z");
}

</style>
