<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1qu2bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:eject" {...props}></Icon>
<style>
:global(.eg1qu2bhb) {
  fill: currentColor;
  d: path("M5 19v-2h14v2zm.35-4L12 5l6.65 10z");
}

</style>
