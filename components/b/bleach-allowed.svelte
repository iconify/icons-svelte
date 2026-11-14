<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mros15bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:bleach-allowed" {...props}></Icon>
<style>
:global(.mros15bdc) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.167 5.76l6.473 11.243q.72 1.25-.003 2.499q-.722 1.248-2.164 1.248H5.527q-1.442 0-2.164-1.248q-.723-1.249-.003-2.499L9.833 5.76Q10.554 4.506 12 4.506t2.167 1.254");
}

</style>
