<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="n19rjccuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:black-large-square" {...props}></Icon>
<style>
:global(.n19rjccuv) {
  fill: var(--svg-color--333, #333);
  d: path("M2 2h60v60H2z");
}

</style>
