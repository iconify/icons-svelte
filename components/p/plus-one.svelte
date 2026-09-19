<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7zmuwdse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:plus-one" {...props}></Icon>
<style>
:global(.t7zmuwdse) {
  fill: currentColor;
  d: path("M10 8H8v4H4v2h4v4h2v-4h4v-2h-4zm4.5-1.92V7.9l2.5-.5V18h2V5z");
}

</style>
