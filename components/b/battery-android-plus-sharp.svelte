<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd3c0-b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-plus-sharp" {...props}></Icon>
<style>
:global(.dd3c0-b0p) {
  fill: currentColor;
  d: path("M1 18V6h15v3h-3v6h3v3zm17-2v-3h-3v-2h3V8h2v3h3v2h-3v3z");
}

</style>
