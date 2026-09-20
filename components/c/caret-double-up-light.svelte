<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l6z0gpbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-double-up-light" {...props}></Icon>
<style>
:global(.l6z0gpbws) {
  fill: currentColor;
  d: path("M212.24 195.76a6 6 0 1 1-8.48 8.48L128 128.49l-75.76 75.75a6 6 0 0 1-8.48-8.48l80-80a6 6 0 0 1 8.48 0Zm-160-71.52L128 48.49l75.76 75.75a6 6 0 0 0 8.48-8.48l-80-80a6 6 0 0 0-8.48 0l-80 80a6 6 0 0 0 8.48 8.48");
}

</style>
