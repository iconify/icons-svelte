<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftc1kcc1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chat-bubble-outline-sharp" {...props}></Icon>
<style>
:global(.ftc1kcc1p) {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
