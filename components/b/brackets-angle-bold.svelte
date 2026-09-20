<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="janpid7zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:brackets-angle-bold" {...props}></Icon>
<style>
:global(.janpid7zo) {
  fill: currentColor;
  d: path("M90.12 46.44L38.22 128l51.9 81.56a12 12 0 1 1-20.24 12.88l-56-88a12 12 0 0 1 0-12.88l56-88a12 12 0 0 1 20.24 12.88m152 75.12l-56-88a12 12 0 1 0-20.24 12.88l51.9 81.56l-51.9 81.56a12 12 0 1 0 20.24 12.88l56-88a12 12 0 0 0 0-12.88");
}

</style>
