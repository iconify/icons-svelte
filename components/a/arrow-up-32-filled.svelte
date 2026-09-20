<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v33rc6ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-32-filled" {...props}></Icon>
<style>
:global(.v33rc6ber) {
  fill: currentColor;
  d: path("M16 29c-.69 0-1.25-.56-1.25-1.25V7.213l-7.628 7.432a1.25 1.25 0 1 1-1.744-1.79l9.747-9.497a1.246 1.246 0 0 1 1.75 0l9.747 9.497a1.25 1.25 0 1 1-1.744 1.79L17.25 7.213V27.75c0 .69-.56 1.25-1.25 1.25");
}

</style>
