<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am9mn180j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-charging-60-2-outline-sharp" {...props}></Icon>
<style>
:global(.am9mn180j) {
  fill: currentColor;
  d: path("M2 17V7h14.25l-1.6 2H11v6h4l-.35 2zm14.675 0l.7-4H14l4.8-6h.525l-.7 4H22l-4.8 6z");
}

</style>
