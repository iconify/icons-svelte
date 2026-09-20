<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syb2ea1hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:eject-outline-sharp" {...props}></Icon>
<style>
:global(.syb2ea1hm) {
  fill: currentColor;
  d: path("M5 19v-2h14v2zm.35-4L12 5l6.65 10zm3.7-2h5.9L12 8.6z");
}

</style>
