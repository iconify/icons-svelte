<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7wu9kboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-minus-fill-sharp" {...props}></Icon>
<style>
:global(.y7wu9kboj) {
  fill: currentColor;
  d: path("M3 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m12 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2M3 15h7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
