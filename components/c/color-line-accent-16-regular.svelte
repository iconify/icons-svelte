<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tzy3kacep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:color-line-accent-16-regular" {...props}></Icon>
<style>
:global(.tzy3kacep) {
  fill: currentColor;
  d: path("M2.007 11.414a1.75 1.75 0 0 0 1.958.773l2.397-.655h.001A3.2 3.2 0 0 0 7.44 11h6.06a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-2q0-.044.007-.086");
}

</style>
