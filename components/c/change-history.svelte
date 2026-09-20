<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otil38bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:change-history" {...props}></Icon>
<style>
:global(.otil38bqp) {
  fill: currentColor;
  d: path("M2 20L12 4l10 16z");
}

</style>
