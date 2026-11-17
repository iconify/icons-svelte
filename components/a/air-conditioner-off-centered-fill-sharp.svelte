<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vux6_f6ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:air-conditioner-off-centered-fill-sharp" {...props}></Icon>
<style>
:global(.vux6_f6ol) {
  fill: currentColor;
  d: path("M2 8a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm5 4a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Z");
}

</style>
