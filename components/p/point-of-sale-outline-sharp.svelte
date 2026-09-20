<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqxrgkbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:point-of-sale-outline-sharp" {...props}></Icon>
<style>
:global(.aqxrgkbpm) {
  fill: currentColor;
  d: path("M5 8V2h14v6zm2-2h10V4H7zM2 22v-3h20v3zm0-4l4-9h12l4 9zm6-2h2v-1H8zm0-2h2v-1H8zm0-2h2v-1H8zm3 4h2v-1h-2zm0-2h2v-1h-2zm0-2h2v-1h-2zm3 4h2v-1h-2zm0-2h2v-1h-2zm0-2h2v-1h-2z");
}

</style>
