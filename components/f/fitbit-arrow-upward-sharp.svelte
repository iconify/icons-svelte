<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5uvk-bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fitbit-arrow-upward-sharp" {...props}></Icon>
<style>
:global(.w5uvk-bww) {
  fill: currentColor;
  d: path("M11 18V9.825L7.4 13.4L6 12l6-6l6 6l-1.4 1.4L13 9.825V18Z");
}

</style>
