<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj8dkh-iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-format-strikethrough" {...props}></Icon>
<style>
:global(.uj8dkh-iv) {
  fill: currentColor;
  d: path("M10 19h4v-3h-4zM5 4v3h5v3h4V7h5V4zM3 14h18v-2H3z");
}

</style>
