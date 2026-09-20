<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kvr-hlrym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-left-20-regular" {...props}></Icon>
<style>
:global(.kvr-hlrym) {
  fill: currentColor;
  d: path("M11.372 14.982A1 1 0 0 0 13 14.204V5.797a1 1 0 0 0-1.628-.778L6.649 8.833a1.5 1.5 0 0 0 0 2.334zM12 5.797v8.407l-4.722-3.815a.5.5 0 0 1 0-.778z");
}

</style>
