<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b7u2nhbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pipeline-20-filled" {...props}></Icon>
<style>
:global(.b7u2nhbkc) {
  fill: currentColor;
  d: path("M2 5.5a1.5 1.5 0 0 1 3 0v9a1.5 1.5 0 0 1-3-.001zm13 0v9a1.5 1.5 0 0 0 3 0v-9a1.5 1.5 0 0 0-3 0M14 14V6H6v8z");
}

</style>
