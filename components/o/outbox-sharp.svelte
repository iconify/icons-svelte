<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taqharx_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:outbox-sharp" {...props}></Icon>
<style>
:global(.taqharx_d) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm10.725-5.55Q14.5 14.9 14.8 14H19V5H5v9h4.2q.3.9 1.075 1.45T12 16t1.725-.55M11 14V9.85l-1.6 1.6L8 10l4-4l4 4l-1.4 1.45l-1.6-1.6V14z");
}

</style>
