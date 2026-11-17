<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfqex5thx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:floor-plan-fill-sharp" {...props}></Icon>
<style>
:global(.jfqex5thx) {
  fill: currentColor;
  d: path("M12 2v7a1 1 0 0 0 2 0V2h7a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-7v-9a1 1 0 0 0-2 0v9H3a1 1 0 0 1-1-1v-7h7a1 1 0 0 0 0-2H2V3a1 1 0 0 1 1-1Z");
}

</style>
