<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7wqj2bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:clear-all-outline" {...props}></Icon>
<style>
:global(.r7wqj2bvy) {
  fill: currentColor;
  d: path("M3 17v-2h14v2zm2-4v-2h14v2zm2-4V7h14v2z");
}

</style>
