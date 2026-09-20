<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca0mpnbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-0-outline-sharp" {...props}></Icon>
<style>
:global(.ca0mpnbdi) {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm2-2h15.5V8H3zm18.5-1.5v-5H23v5zM3 16V8z");
}

</style>
