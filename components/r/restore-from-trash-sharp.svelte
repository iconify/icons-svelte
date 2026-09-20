<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzqpp_-4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:restore-from-trash-sharp" {...props}></Icon>
<style>
:global(.uzqpp_-4i) {
  fill: currentColor;
  d: path("M11 16h2v-4.15l1.6 1.55L16 12l-4-4l-4 4l1.4 1.4l1.6-1.55zm-6 5V6H4V4h5V3h6v1h5v2h-1v15z");
}

</style>
