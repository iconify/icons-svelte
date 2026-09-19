<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="x2xu2umfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:heavy-minus-sign" {...props}></Icon>
<style>
:global(.x2xu2umfc) {
  fill: currentColor;
  d: path("M2 26h60v12H2z");
}

</style>
