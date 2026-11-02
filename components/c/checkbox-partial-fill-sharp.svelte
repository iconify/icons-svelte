<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9hcurb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:checkbox-partial-fill-sharp" {...props}></Icon>
<style>
:global(.r9hcurb1d) {
  fill: currentColor;
  d: path("M3 20V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m12-9H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
