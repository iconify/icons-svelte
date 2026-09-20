<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h40kz-a6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:lightbulb-16-filled" {...props}></Icon>
<style>
:global(.h40kz-a6o) {
  fill: currentColor;
  d: path("M8 2a4.5 4.5 0 0 0-3.155 7.708a.65.65 0 0 1 .18.287L5.3 11h5.4l.274-1.005a.65.65 0 0 1 .181-.287A4.5 4.5 0 0 0 8 2m2.427 10H5.573l.244.895A1.5 1.5 0 0 0 7.264 14h1.472a1.5 1.5 0 0 0 1.447-1.105z");
}

</style>
