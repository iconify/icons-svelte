<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ctuz6eght"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:circle-big-filled" {...props}></Icon>
<style>
:global(.ctuz6eght) {
  fill: currentColor;
  d: path("M19.5 10a9.5 9.5 0 1 1-19 0a9.5 9.5 0 0 1 19 0");
}

</style>
