<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5hi5oq4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-fast-rewind" {...props}></Icon>
<style>
:global(.g5hi5oq4a) {
  fill: currentColor;
  d: path("M11 18V6l-8.5 6zm.5-6l8.5 6V6z");
}

</style>
