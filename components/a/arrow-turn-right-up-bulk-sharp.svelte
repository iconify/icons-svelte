<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1x2bcb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-right-up-bulk-sharp" {...props}></Icon>
<style>
:global(.p1x2bcb2i) {
  fill: currentColor;
  d: path("M15 16V9.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414l5-5a1 1 0 0 1 1.414 0l5 5a.999.999 0 1 1-1.414 1.414L17 9.414V17a1 1 0 0 1-1 1H3a1 1 0 0 1 0-2Z");
}

</style>
