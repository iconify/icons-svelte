<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj9crxbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-to-queue-sharp" {...props}></Icon>
<style>
:global(.vj9crxbto) {
  fill: currentColor;
  d: path("M11 15h2v-3h3v-2h-3V7h-2v3H8v2h3zm-3 6v-2H2V3h20v16h-6v2z");
}

</style>
