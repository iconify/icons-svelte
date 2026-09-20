<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zznvuz0ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mark-chat-read-sharp" {...props}></Icon>
<style>
:global(.zznvuz0ej) {
  fill: currentColor;
  d: path("m17.35 20l-3.525-3.55l1.4-1.4l2.125 2.125l4.25-4.25L23 14.35zM2 22V2h20v9H12v7H6z");
}

</style>
