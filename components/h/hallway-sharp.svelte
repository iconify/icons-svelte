<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmlgg6klm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hallway-sharp" {...props}></Icon>
<style>
:global(.wmlgg6klm) {
  fill: currentColor;
  d: path("M3 22V4h5l4-4l4 4h5v18zm3-4h12l-3.75-5l-3 4L9 14zm4.1-14h3.8L12 2.1z");
}

</style>
