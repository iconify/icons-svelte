<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bydkv6rsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:camera-outdoor-sharp" {...props}></Icon>
<style>
:global(.bydkv6rsh) {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v2h-9v8h9v2zm8-3v-6h6v2l2-1.05v4.1L18 16v2z");
}

</style>
