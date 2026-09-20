<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytixpqzsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:broken-image-sharp" {...props}></Icon>
<style>
:global(.ytixpqzsh) {
  fill: currentColor;
  d: path("M4 20v-7.292l2 2l4-4l4 4l4-4l2 2V20zM4 4h16v7.287l-2-2l-4 4l-4-4l-4 4l-2-2z");
}

</style>
