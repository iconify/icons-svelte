<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wnuhcllkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:intersection-light" {...props}></Icon>
<style>
:global(.wnuhcllkz) {
  fill: currentColor;
  d: path("M206 120v80a6 6 0 0 1-12 0v-80a66 66 0 0 0-132 0v80a6 6 0 0 1-12 0v-80a78 78 0 0 1 156 0");
}

</style>
