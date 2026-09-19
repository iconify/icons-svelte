<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsua6gmxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:call-received" {...props}></Icon>
<style>
:global(.rsua6gmxm) {
  fill: currentColor;
  d: path("M20 5.41L18.59 4L7 15.59V9H5v10h10v-2H8.41z");
}

</style>
