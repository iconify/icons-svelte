<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1v77_hyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-24-filled" {...props}></Icon>
<style>
:global(.v1v77_hyg) {
  fill: currentColor;
  d: path("M21.707 2.293a1 1 0 0 1 0 1.414l-18 18a1 1 0 0 1-1.414-1.414l18-18a1 1 0 0 1 1.414 0");
}

</style>
