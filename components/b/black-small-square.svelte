<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ddovr0uap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:black-small-square" {...props}></Icon>
<style>
:global(.ddovr0uap) {
  fill: var(--svg-color--333, #333);
  d: path("M16 16h32v32H16z");
}

</style>
