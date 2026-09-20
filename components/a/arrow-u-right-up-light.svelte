<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tk1gkq-av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-u-right-up-light" {...props}></Icon>
<style>
:global(.tk1gkq-av) {
  fill: currentColor;
  d: path("M220.24 84.24a6 6 0 0 1-8.48 0L174 46.49V168a62 62 0 0 1-124 0V80a6 6 0 0 1 12 0v88a50 50 0 0 0 100 0V46.49l-37.76 37.75a6 6 0 0 1-8.48-8.48l48-48a6 6 0 0 1 8.48 0l48 48a6 6 0 0 1 0 8.48");
}

</style>
