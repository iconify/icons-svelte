<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f0v_76der"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cursor-hover-32-filled" {...props}></Icon>
<style>
:global(.f0v_76der) {
  fill: currentColor;
  d: path("M2 10a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4v10a4 4 0 0 1-2.328 3.635a3 3 0 0 0-.55-.756l-8-8A3 3 0 0 0 14 17v7H6a4 4 0 0 1-4-4zm14 19a1 1 0 0 0 1.8.6l2.7-3.6H25a1 1 0 0 0 .707-1.707l-8-8A1 1 0 0 0 16 17z");
}

</style>
