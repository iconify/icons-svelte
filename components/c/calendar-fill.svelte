<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw6dftnoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-fill" {...props}></Icon>
<style>
:global(.tw6dftnoy) {
  fill: currentColor;
  d: path("M9 3v1h6V3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3.004 3.004 0 0 1-3-3V7a3 3 0 0 1 3-3h1V3a1 1 0 0 1 2 0m-4 7v9a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-9Z");
}

</style>
