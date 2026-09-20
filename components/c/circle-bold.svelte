<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ogpo9i6fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:circle-bold" {...props}></Icon>
<style>
:global(.ogpo9i6fz) {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84");
}

</style>
