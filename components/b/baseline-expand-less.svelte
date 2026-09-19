<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpb10db7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-expand-less" {...props}></Icon>
<style>
:global(.bpb10db7x) {
  fill: currentColor;
  d: path("m12 8l-6 6l1.41 1.41L12 10.83l4.59 4.58L18 14z");
}

</style>
