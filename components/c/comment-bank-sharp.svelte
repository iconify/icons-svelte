<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl6lqk5vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:comment-bank-sharp" {...props}></Icon>
<style>
:global(.fl6lqk5vz) {
  fill: currentColor;
  d: path("M12.5 11L15 9.5l2.5 1.5V4h-5zM2 22V2h20v16H6z");
}

</style>
