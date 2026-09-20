<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4e6nwbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-full-outline-sharp" {...props}></Icon>
<style>
:global(.i4e6nwbag) {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm20.5-3.5v-5H23v5z");
}

</style>
