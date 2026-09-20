<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewjqn0bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-square-20-filled" {...props}></Icon>
<style>
:global(.ewjqn0bug) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm7.5.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 1 0 1 0v-3h3a.5.5 0 1 0 0-1h-3z");
}

</style>
