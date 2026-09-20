<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="s6ao7ubvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:clock-afternoon-bold" {...props}></Icon>
<style>
:global(.s6ao7ubvv) {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m68-84a12 12 0 0 1-12 12h-27l19.52 19.51a12 12 0 0 1-17 17l-40-40A12 12 0 0 1 128 116h56a12 12 0 0 1 12 12");
}

</style>
