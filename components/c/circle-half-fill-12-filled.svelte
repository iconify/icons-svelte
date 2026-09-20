<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="azc888bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-half-fill-12-filled" {...props}></Icon>
<style>
:global(.azc888bir) {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m1.5 0h7a3.5 3.5 0 1 0-7 0");
}

</style>
