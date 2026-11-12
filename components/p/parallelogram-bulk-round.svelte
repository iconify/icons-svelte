<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1vekci8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:parallelogram-bulk-round" {...props}></Icon>
<style>
:global(.p1vekci8w) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m21.976 3.217l-4 18A1 1 0 0 1 17 22H3a1.002 1.002 0 0 1-.976-1.217l4-18A1 1 0 0 1 7 2h14a1.002 1.002 0 0 1 .976 1.217");
}

</style>
