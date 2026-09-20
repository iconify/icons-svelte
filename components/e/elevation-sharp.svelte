<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4zmg3v2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:elevation-sharp" {...props}></Icon>
<style>
:global(.w4zmg3v2i) {
  fill: currentColor;
  d: path("m3.685 19.192l5.007-7h5.012l5.988-6.988v13.988zm.038-4.401l-.792-.574l3.858-5.41h5.03l4.508-5.282l.77.666l-4.84 5.617H7.29z");
}

</style>
