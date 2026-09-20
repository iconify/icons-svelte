<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nj3d7zwml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:grab" {...props}></Icon>
<style>
:global(.nj3d7zwml) {
  fill: currentColor;
  d: path("M2.5 8a1 1 0 0 1 0-2h15a1 1 0 1 1 0 2zm0 3.25a1 1 0 1 1 0-2h15a1 1 0 1 1 0 2zm0 3.25a1 1 0 1 1 0-2h15a1 1 0 1 1 0 2z");
}

</style>
