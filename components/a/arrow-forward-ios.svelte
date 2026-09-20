<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu_r9fbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-forward-ios" {...props}></Icon>
<style>
:global(.nu_r9fbhm) {
  fill: currentColor;
  d: path("M8.025 22L6.25 20.225L14.475 12L6.25 3.775L8.025 2l10 10z");
}

</style>
