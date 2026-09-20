<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlr11mb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:airlines" {...props}></Icon>
<style>
:global(.mlr11mb7o) {
  fill: currentColor;
  d: path("M2 20L13 4h9l-3 16zm12.5-6q1.05 0 1.775-.725T17 11.5t-.725-1.775T14.5 9t-1.775.725T12 11.5t.725 1.775T14.5 14");
}

</style>
