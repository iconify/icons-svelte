<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziul6bkgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:camera-indoor-outline-sharp" {...props}></Icon>
<style>
:global(.ziul6bkgs) {
  fill: currentColor;
  d: path("M8.539 16.616h5.23v-2.077l1.847.973v-3.023l-1.847.973v-2.077H8.54zM5 20V9.5l7-5.27l7 5.27V20zm1-1h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
