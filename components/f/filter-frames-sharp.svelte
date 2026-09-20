<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1q0lk8xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-frames-sharp" {...props}></Icon>
<style>
:global(.k1q0lk8xi) {
  fill: currentColor;
  d: path("M2 22V4h6l4-4l4 4h6v18zm2-2h16V6H4zm2-2V8h12v10z");
}

</style>
