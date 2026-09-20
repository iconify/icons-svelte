<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dtbymwbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-48-filled" {...props}></Icon>
<style>
:global(.dtbymwbfv) {
  fill: currentColor;
  d: path("M40.317 12.695a1.5 1.5 0 0 1-.012 2.122l-22.25 22a1.5 1.5 0 0 1-2.101.008l-9.25-9a1.5 1.5 0 1 1 2.092-2.15l8.196 7.974l21.203-20.966a1.5 1.5 0 0 1 2.122.012");
}

</style>
