<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmf5k0k8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-arrow-notch" {...props}></Icon>
<style>
:global(.kmf5k0k8q) {
  fill: currentColor;
  d: path("m11 19l3.425-6H2v-2h12.425L11 5l11 7z");
}

</style>
