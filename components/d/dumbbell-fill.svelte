<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvaohjbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dumbbell-fill" {...props}></Icon>
<style>
:global(.bvaohjbje) {
  fill: currentColor;
  d: path("M6 4h2a2 2 0 0 1 2 2v5h4V6a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-5h-4v5a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2V6a2 2 0 0 1 2-2");
}

</style>
