<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2cy5k4ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:north" {...props}></Icon>
<style>
:global(.k2cy5k4ap) {
  fill: currentColor;
  d: path("M11 22V5.825L6.4 10.4L5 9l7-7l7 7l-1.4 1.425l-4.6-4.6V22z");
}

</style>
