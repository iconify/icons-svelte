<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brmof2bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-start-arrow-notch-sharp" {...props}></Icon>
<style>
:global(.brmof2bgs) {
  fill: currentColor;
  d: path("M11.808 16.827L4.212 12l7.596-4.827L9.402 11.5H21.5v1H9.402z");
}

</style>
