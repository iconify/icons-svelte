<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wumpg3bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-arrow-up-outline-sharp" {...props}></Icon>
<style>
:global(.wumpg3bps) {
  fill: currentColor;
  d: path("m12 10.108l-4.6 4.6L6.692 14L12 8.692L17.308 14l-.708.708z");
}

</style>
