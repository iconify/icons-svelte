<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cs3q92bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:mouse-simple-thin" {...props}></Icon>
<style>
:global(.cs3q92bdt) {
  fill: currentColor;
  d: path("M144 20h-32a60.07 60.07 0 0 0-60 60v96a60.07 60.07 0 0 0 60 60h32a60.07 60.07 0 0 0 60-60V80a60.07 60.07 0 0 0-60-60m52 156a52.06 52.06 0 0 1-52 52h-32a52.06 52.06 0 0 1-52-52V80a52.06 52.06 0 0 1 52-52h32a52.06 52.06 0 0 1 52 52ZM132 64v48a4 4 0 0 1-8 0V64a4 4 0 0 1 8 0");
}

</style>
