<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nd5c-2b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-up-right-thin" {...props}></Icon>
<style>
:global(.nd5c-2b8q) {
  fill: currentColor;
  d: path("m218.83 82.83l-48 48a4 4 0 0 1-5.66-5.66L206.34 84H76v140a4 4 0 0 1-8 0V80a4 4 0 0 1 4-4h134.34l-41.17-41.17a4 4 0 0 1 5.66-5.66l48 48a4 4 0 0 1 0 5.66");
}

</style>
