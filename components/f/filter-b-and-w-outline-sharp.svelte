<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e348o2hja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-b-and-w-outline-sharp" {...props}></Icon>
<style>
:global(.e348o2hja) {
  fill: currentColor;
  d: path("M21 21H3V3h18zM5 19h7v-8l7 8V5h-7v6z");
}

</style>
