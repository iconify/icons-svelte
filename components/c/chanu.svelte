<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dzti1dbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chanu" {...props}></Icon>
<style>
:global(.dzti1dbge) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 24A9.25 9.25 0 1 1 24 14.75V24ZM24 14.75A9.25 9.25 0 1 1 33.25 24H24ZM33.25 24A9.25 9.25 0 1 1 24 33.25V24ZM24 33.25A9.25 9.25 0 1 1 14.75 24H24Z");
}

</style>
