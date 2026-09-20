<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u8svc2bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rectangle-fill" {...props}></Icon>
<style>
:global(.u8svc2bpg) {
  fill: currentColor;
  d: path("M232 56v144a16 16 0 0 1-16 16H40a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16h176a16 16 0 0 1 16 16");
}

</style>
