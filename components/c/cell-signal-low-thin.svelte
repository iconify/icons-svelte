<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hjd8-pbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-low-thin" {...props}></Icon>
<style>
:global(.hjd8-pbkw) {
  fill: currentColor;
  d: path("M84 152v48a4 4 0 0 1-8 0v-48a4 4 0 0 1 8 0m-44 36a4 4 0 0 0-4 4v8a4 4 0 0 0 8 0v-8a4 4 0 0 0-4-4");
}

</style>
