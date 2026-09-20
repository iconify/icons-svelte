<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlwby3b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-2-sharp" {...props}></Icon>
<style>
:global(.jlwby3b8d) {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm7-2h10.5V8H8zm13.5-1.5v-5H23v5z");
}

</style>
