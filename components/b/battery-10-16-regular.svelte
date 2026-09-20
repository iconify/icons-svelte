<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nklkrcc1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:battery-10-16-regular" {...props}></Icon>
<style>
:global(.nklkrcc1a) {
  fill: currentColor;
  d: path("M4 6h7.5v4H4zm9.5.5h.5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5h-.5v.5c0 1.103-.897 2-2 2H4c-1.103 0-2-.897-2-2V6c0-1.103.897-2 2-2h7.5c1.103 0 2 .897 2 2zm-2 4.5a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1z");
}

</style>
