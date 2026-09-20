<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l7uq90bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:doctor-12-filled" {...props}></Icon>
<style>
:global(.l7uq90bnb) {
  fill: currentColor;
  d: path("M5 2a1 1 0 0 0-1 1v1H3a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h1v1a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V8h1a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1H8V3a1 1 0 0 0-1-1z");
}

</style>
