<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rlwbb2btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-32-light" {...props}></Icon>
<style>
:global(.rlwbb2btz) {
  fill: currentColor;
  d: path("M16.5 3.5a.5.5 0 0 0-1 0v12h-12a.5.5 0 0 0 0 1h12v12a.5.5 0 0 0 1 0v-12h12a.5.5 0 0 0 0-1h-12z");
}

</style>
