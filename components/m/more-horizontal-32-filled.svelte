<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qf2c3kgra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-horizontal-32-filled" {...props}></Icon>
<style>
:global(.qf2c3kgra) {
  fill: currentColor;
  d: path("M7 19a3 3 0 1 0 0-6a3 3 0 0 0 0 6m9 0a3 3 0 1 0 0-6a3 3 0 0 0 0 6m9 0a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
