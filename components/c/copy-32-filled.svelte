<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e2o4n2bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:copy-32-filled" {...props}></Icon>
<style>
:global(.e2o4n2bxn) {
  fill: currentColor;
  d: path("M10.5 19.5a6 6 0 0 0 6 6h3.387A4.5 4.5 0 0 1 15.5 29h-8A4.5 4.5 0 0 1 3 24.5v-12A4.5 4.5 0 0 1 7.5 8h3zM24.5 3A4.5 4.5 0 0 1 29 7.5v12a4.5 4.5 0 0 1-4.5 4.5h-8a4.5 4.5 0 0 1-4.5-4.5v-12A4.5 4.5 0 0 1 16.5 3z");
}

</style>
