<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-d04i3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flag-2" {...props}></Icon>
<style>
:global(.gr-d04i3s) {
  fill: currentColor;
  d: path("M5 22V3h16l-2 5l2 5H7v9z");
}

</style>
