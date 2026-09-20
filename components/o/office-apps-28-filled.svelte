<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="t7bmuwbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:office-apps-28-filled" {...props}></Icon>
<style>
:global(.t7bmuwbge) {
  fill: currentColor;
  d: path("M14 20a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m8.5 0a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-17 0a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m8.5-8.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m8.5 0a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-17 0a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5M14 3a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m8.5 0a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-17 0a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
