<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ry69nsbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:black-medium-square" {...props}></Icon>
<style>
:global(.ry69nsbrv) {
  fill: var(--svg-color--333, #333);
  d: path("M8 8h48v48H8z");
}

</style>
