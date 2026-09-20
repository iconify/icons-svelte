<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n5fwackel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:hand-grabbing-fill" {...props}></Icon>
<style>
:global(.n5fwackel) {
  fill: currentColor;
  d: path("M216 104v48a88 88 0 0 1-176 0v-16a16 16 0 0 1 32 0v8a8 8 0 0 0 16 0V88a16 16 0 0 1 32 0v16a8 8 0 0 0 16 0V88a16 16 0 0 1 32 0v16a8 8 0 0 0 16 0a16 16 0 0 1 32 0");
}

</style>
