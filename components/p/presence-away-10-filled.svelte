<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="wnmqn3b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-away-10-filled" {...props}></Icon>
<style>
:global(.wnmqn3b2o) {
  fill: currentColor;
  d: path("M5 10A5 5 0 1 0 5 0a5 5 0 0 0 0 10m0-6.996v1.79l1.354 1.353a.5.5 0 1 1-.708.707l-1.5-1.5A.5.5 0 0 1 4 5V3.004a.5.5 0 0 1 1 0");
}

</style>
