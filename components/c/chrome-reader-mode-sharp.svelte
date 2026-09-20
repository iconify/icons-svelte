<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckrbk0gmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chrome-reader-mode-sharp" {...props}></Icon>
<style>
:global(.ckrbk0gmo) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm11-2h7V6h-7zm1-8h5V8.5h-5zm0 2.5h5V11h-5zm0 2.5h5v-1.5h-5z");
}

</style>
