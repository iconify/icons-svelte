<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2hc5bcan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-outward-outline-sharp" {...props}></Icon>
<style>
:global(.u2hc5bcan) {
  fill: currentColor;
  d: path("M6.4 18L5 16.6L14.6 7H6V5h12v12h-2V8.4z");
}

</style>
