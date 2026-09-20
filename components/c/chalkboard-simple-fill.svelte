<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tzszduaiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chalkboard-simple-fill" {...props}></Icon>
<style>
:global(.tzszduaiz) {
  fill: currentColor;
  d: path("M240 192h-8V56a16 16 0 0 0-16-16H40a16 16 0 0 0-16 16v136h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16m-24 0h-72v-16a8 8 0 0 1 8-8h56a8 8 0 0 1 8 8Z");
}

</style>
