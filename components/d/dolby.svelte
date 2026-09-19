<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ini7ytuhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dolby" {...props}></Icon>
<style>
:global(.ini7ytuhj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.182 11.59H43.5v24.82h0h-5.318A12.41 12.41 0 0 1 25.772 24v0a12.41 12.41 0 0 1 12.41-12.41M9.818 36.41H4.5h0V11.59h5.318A12.41 12.41 0 0 1 22.227 24h0a12.41 12.41 0 0 1-12.41 12.41");
}

</style>
