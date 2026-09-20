<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5911o9vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-drop-up-outline" {...props}></Icon>
<style>
:global(.d5911o9vi) {
  fill: currentColor;
  d: path("m7 14l5-5l5 5z");
}

</style>
