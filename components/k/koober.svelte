<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a28xsovsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:koober" {...props}></Icon>
<style>
:global(.a28xsovsv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.006 8.33c3.773-3.773 9.89-3.773 13.664 0s3.773 9.89 0 13.664L21.994 39.67a9.66 9.66 0 0 1-13.664 0a9.66 9.66 0 0 1 0-13.664z");
}

</style>
