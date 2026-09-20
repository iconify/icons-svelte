<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pqbn7cb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-left-32-regular" {...props}></Icon>
<style>
:global(.pqbn7cb2i) {
  fill: currentColor;
  d: path("M17.004 28.996a1 1 0 1 0 0-2H6.418L28.707 4.707a1 1 0 0 0-1.414-1.414L5.003 25.582V14.996a1 1 0 1 0-2 0v13a1 1 0 0 0 1 1z");
}

</style>
