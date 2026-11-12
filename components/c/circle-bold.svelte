<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="viqqom1is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-bold" {...props}></Icon>
<style>
:global(.viqqom1is) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 12C22 17.523 17.5228 22 12 22C6.4772 22 2 17.523 2 12C2 6.477 6.4772 2 12 2C17.5228 2 22 6.477 22 12Z");
}

</style>
