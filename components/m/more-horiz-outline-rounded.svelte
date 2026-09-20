<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v10iw94hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:more-horiz-outline-rounded" {...props}></Icon>
<style>
:global(.v10iw94hf) {
  fill: currentColor;
  d: path("M6.462 13q-.413 0-.707-.294T5.462 12t.293-.706t.707-.294t.706.294t.293.706t-.293.706T6.46 13M12 13q-.413 0-.706-.294T11 12t.294-.706T12 11t.706.294T13 12t-.294.706T12 13m5.539 0q-.413 0-.707-.294T16.538 12t.294-.706t.706-.294t.707.294t.293.706t-.293.706t-.707.294");
}

</style>
