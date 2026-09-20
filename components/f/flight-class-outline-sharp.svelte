<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgc6n_jgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flight-class-outline-sharp" {...props}></Icon>
<style>
:global(.wgc6n_jgl) {
  fill: currentColor;
  d: path("M12 13V4h6v9zm2-2h2V6h-2zm4 7H8L5 8V4h2v4l2.5 8H18zM8 21v-2h10v2zm6-15h2z");
}

</style>
