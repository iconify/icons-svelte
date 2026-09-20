<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ua9u1rrzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rectangle-bold" {...props}></Icon>
<style>
:global(.ua9u1rrzw) {
  fill: currentColor;
  d: path("M216 36H40a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 160H44V60h168Z");
}

</style>
