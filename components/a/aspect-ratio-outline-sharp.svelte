<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xha3dx-sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:aspect-ratio-outline-sharp" {...props}></Icon>
<style>
:global(.xha3dx-sd) {
  fill: currentColor;
  d: path("M14 17h5v-5h-2v3h-3zm-9-5h2V9h3V7H5zm-3 8V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
