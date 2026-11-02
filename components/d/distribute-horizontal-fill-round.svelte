<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndcj8zbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-horizontal-fill-round" {...props}></Icon>
<style>
:global(.ndcj8zbpr) {
  fill: currentColor;
  d: path("M5 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm16 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM8 9a4 4 0 0 1 8 0v6a4 4 0 0 1-8 0Z");
}

</style>
