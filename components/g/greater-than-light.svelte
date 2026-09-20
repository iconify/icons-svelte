<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wggz6tmor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:greater-than-light" {...props}></Icon>
<style>
:global(.wggz6tmor) {
  fill: currentColor;
  d: path("M222 128a6 6 0 0 1-3.43 5.42l-152 72a6 6 0 1 1-5.14-10.84L202 128L61.43 61.42a6 6 0 1 1 5.14-10.84l152 72A6 6 0 0 1 222 128");
}

</style>
