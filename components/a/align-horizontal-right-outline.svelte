<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpoderofg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-horizontal-right-outline" {...props}></Icon>
<style>
:global(.bpoderofg) {
  fill: currentColor;
  d: path("M20 22V2h2v20zM8 17v-3h10v3zm-6-7V7h16v3z");
}

</style>
