<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1kp8156m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:camera-indoor-sharp" {...props}></Icon>
<style>
:global(.w1kp8156m) {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.27l7 5.27V20zm3.539-3.384h5.23v-2.077l1.846.973v-3.023l-1.846.973v-2.077H8.54z");
}

</style>
