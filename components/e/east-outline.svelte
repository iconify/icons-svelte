<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmkmlebje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:east-outline" {...props}></Icon>
<style>
:global(.tmkmlebje) {
  fill: currentColor;
  d: path("m15 19l-1.425-1.4l4.6-4.6H2v-2h16.175L13.6 6.4L15 5l7 7z");
}

</style>
