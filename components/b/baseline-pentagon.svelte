<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f51axpbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-pentagon" {...props}></Icon>
<style>
:global(.f51axpbuv) {
  fill: currentColor;
  d: path("m2 9l4 12h12l4-12l-10-7z");
}

</style>
