<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbpay4bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-to-line-fill" {...props}></Icon>
<style>
:global(.fbpay4bms) {
  fill: currentColor;
  d: path("M6.707 6.293L12 11.586l5.293-5.293a.999.999 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6a.999.999 0 1 1 1.414-1.414M18 16a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
