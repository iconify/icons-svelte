<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8jwovpxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mushroom-fill" {...props}></Icon>
<style>
:global(.t8jwovpxe) {
  fill: currentColor;
  d: path("M20 12h-5v7a3 3 0 1 1-6 0v-7H4a1 1 0 0 1-1-1a9 9 0 0 1 9-9a9 9 0 0 1 9 9a1 1 0 0 1-1 1");
}

</style>
