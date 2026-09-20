<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yay6clblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bed-light" {...props}></Icon>
<style>
:global(.yay6clblu) {
  fill: currentColor;
  d: path("M216 74H30V48a6 6 0 0 0-12 0v160a6 6 0 0 0 12 0v-34h212v34a6 6 0 0 0 12 0v-96a38 38 0 0 0-38-38M30 86h76v76H30Zm88 76V86h98a26 26 0 0 1 26 26v50Z");
}

</style>
