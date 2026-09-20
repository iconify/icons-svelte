<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o1txt7bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:notebook-section-20-regular" {...props}></Icon>
<style>
:global(.o1txt7bzx) {
  fill: currentColor;
  d: path("M14 2.5a.5.5 0 0 0-1 0V3H8a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h5v.5a.5.5 0 0 0 1 0zM13 16H8a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h5z");
}

</style>
