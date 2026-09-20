<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8rm69byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-end-arrow-notch-outline" {...props}></Icon>
<style>
:global(.t8rm69byn) {
  fill: currentColor;
  d: path("m12.192 16.827l2.406-4.327H2.5v-1h12.098l-2.406-4.327L19.788 12z");
}

</style>
