<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp4w0bcke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:polyline-sharp" {...props}></Icon>
<style>
:global(.yp4w0bcke) {
  fill: currentColor;
  d: path("M15.5 21.5v-2.308L8.116 15.5H3.5v-5h4.03l2.97-3.408V2.5h5v5h-4.03L8.5 10.908v3.65l7 3.5V16.5h5v5z");
}

</style>
