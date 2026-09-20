<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yzo91tkvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:eye-show-24-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.yzo91tkvi) {
  d: path("M12 9.005a4 4 0 1 1 0 8a4 4 0 0 1 0-8zM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365a8.503 8.503 0 0 0-16.493.004a.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5z");
  fill: currentColor;
}

</style>
