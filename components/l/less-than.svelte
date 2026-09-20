<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dvsx2kb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:less-than" {...props}></Icon>
<style>
:global(.dvsx2kb7s) {
  fill: currentColor;
  d: path("M207.23 203.42a8 8 0 0 1-10.66 3.81l-152-72a8 8 0 0 1 0-14.46l152-72a8 8 0 1 1 6.85 14.46L66.69 128l136.73 64.77a8 8 0 0 1 3.81 10.65");
}

</style>
