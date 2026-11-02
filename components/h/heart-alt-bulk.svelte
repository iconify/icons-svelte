<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-i06bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-alt-bulk" {...props}></Icon>
<style>
:global(.yx-i06bfg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12 5.586l.293-.293a5.243 5.243 0 0 1 7.414 7.414l-6 6a2.414 2.414 0 0 1-3.414 0l-6-6a5.243 5.243 0 0 1 7.414-7.414Z");
}

</style>
