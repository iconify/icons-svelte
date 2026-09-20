<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrez5ybmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-arrow-down" {...props}></Icon>
<style>
:global(.wrez5ybmg) {
  fill: currentColor;
  d: path("M12 14.708L6.692 9.4l.708-.708l4.6 4.6l4.6-4.6l.708.708z");
}

</style>
