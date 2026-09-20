<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g-j74pbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dismiss-16-regular" {...props}></Icon>
<style>
:global(.g-j74pbak) {
  fill: currentColor;
  d: path("m2.589 2.716l.057-.07a.5.5 0 0 1 .638-.057l.07.057L8 7.293l4.646-4.647a.5.5 0 0 1 .708.708L8.707 8l4.647 4.646a.5.5 0 0 1 .057.638l-.057.07a.5.5 0 0 1-.638.057l-.07-.057L8 8.707l-4.646 4.647a.5.5 0 0 1-.708-.708L7.293 8L2.646 3.354a.5.5 0 0 1-.057-.638l.057-.07z");
}

</style>
