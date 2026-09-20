<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s9x4u3bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-two-20-filled" {...props}></Icon>
<style>
:global(.s9x4u3bnz) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v3.5H3zm0 4.5V14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3v-3.5z");
}

</style>
