<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_ur5gfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-charging-50-2-outline-sharp" {...props}></Icon>
<style>
:global(.pv_ur5gfj) {
  fill: currentColor;
  d: path("M2 17V7h14.25l-1.6 2H10v6h5l-.35 2zm14.675 0l.7-4H14l4.8-6h.525l-.7 4H22l-4.8 6z");
}

</style>
