<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ricnnkb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-empty-fill-sharp" {...props}></Icon>
<style>
:global(.ricnnkb6w) {
  fill: currentColor;
  d: path("M2 17V7a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m20-3a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
