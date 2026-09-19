<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mh07l-bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:black-small-square" {...props}></Icon>
<style>
:global(.mh07l-bzv) {
  fill: currentColor;
  d: path("M16 16h32v32H16z");
}

</style>
