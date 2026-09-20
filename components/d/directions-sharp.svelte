<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wonepdvpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:directions-sharp" {...props}></Icon>
<style>
:global(.wonepdvpb) {
  fill: currentColor;
  d: path("M8 15h2v-3h3.5v2.5L17 11l-3.5-3.5V10H8zm4 7.8L1.2 12L12 1.2L22.8 12z");
}

</style>
