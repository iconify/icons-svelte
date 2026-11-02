<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq1ge0_ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-21-9-fill-round" {...props}></Icon>
<style>
:global(.aq1ge0_ym) {
  fill: currentColor;
  d: path("M7 7h10a5 5 0 0 1 0 10H7A5 5 0 0 1 7 7");
}

</style>
