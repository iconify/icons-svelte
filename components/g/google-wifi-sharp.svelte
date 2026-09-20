<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iso48en0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:google-wifi-sharp" {...props}></Icon>
<style>
:global(.iso48en0p) {
  fill: currentColor;
  d: path("M2.6 10L3 4h18l.4 6zM5 20l-.325-1H2l.475-7h19.05L22 19h-2.675L19 20z");
}

</style>
