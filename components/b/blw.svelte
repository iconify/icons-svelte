<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c4ryhprgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blw" {...props}></Icon>
<style>
:global(.c4ryhprgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.857 26.893H10.448L32.333 4.5l-8.19 16.607h13.409L15.667 43.5z");
}

</style>
