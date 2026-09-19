<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cbs_dha_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:black-large-square" {...props}></Icon>
<style>
:global(.cbs_dha_p) {
  fill: currentColor;
  d: path("M2 2h60v60H2z");
}

</style>
