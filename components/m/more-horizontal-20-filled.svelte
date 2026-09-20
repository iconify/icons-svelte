<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oc53ydthm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-horizontal-20-filled" {...props}></Icon>
<style>
:global(.oc53ydthm) {
  fill: currentColor;
  d: path("M6.75 10a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0m5 0a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0M15 11.75a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5");
}

</style>
