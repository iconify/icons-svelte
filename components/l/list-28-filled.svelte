<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="pa9-_yb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:list-28-filled" {...props}></Icon>
<style>
:global(.pa9-_yb1d) {
  fill: currentColor;
  d: path("M3 7a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m0 14a1 1 0 0 1 1-1h16a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m1-8a1 1 0 1 0 0 2h20a1 1 0 1 0 0-2z");
}

</style>
