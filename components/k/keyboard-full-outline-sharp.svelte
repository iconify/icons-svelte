<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpr2rkb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-full-outline-sharp" {...props}></Icon>
<style>
:global(.kpr2rkb5k) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-6h16V6H4z");
}

</style>
