<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smjywgqfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-keyboard-control-key" {...props}></Icon>
<style>
:global(.smjywgqfj) {
  fill: currentColor;
  d: path("m5 12l1.41 1.41L12 7.83l5.59 5.58L19 12l-7-7z");
}

</style>
