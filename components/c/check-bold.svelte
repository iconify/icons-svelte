<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mstpgkbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:check-bold" {...props}></Icon>
<style>
:global(.mstpgkbvu) {
  fill: currentColor;
  d: path("m232.49 80.49l-128 128a12 12 0 0 1-17 0l-56-56a12 12 0 1 1 17-17L96 183L215.51 63.51a12 12 0 0 1 17 17Z");
}

</style>
