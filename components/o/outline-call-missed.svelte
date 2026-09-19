<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsz3opb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-call-missed" {...props}></Icon>
<style>
:global(.bsz3opb4z) {
  fill: currentColor;
  d: path("M19.59 7L12 14.59L6.41 9H11V7H3v8h2v-4.59l7 7l9-9z");
}

</style>
