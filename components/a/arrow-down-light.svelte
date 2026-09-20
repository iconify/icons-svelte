<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l6ducsblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-down-light" {...props}></Icon>
<style>
:global(.l6ducsblg) {
  fill: currentColor;
  d: path("m204.24 148.24l-72 72a6 6 0 0 1-8.48 0l-72-72a6 6 0 0 1 8.48-8.48L122 201.51V40a6 6 0 0 1 12 0v161.51l61.76-61.75a6 6 0 0 1 8.48 8.48");
}

</style>
