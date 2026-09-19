<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="s4so8m5md"/><circle class="rt_37l3dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:eleven-oclock" {...props}></Icon>
<style>
:global(.rt_37l3dj) {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

:global(.s4so8m5md) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m2 36h-4v-2.555c-1.19-.693-2-1.969-2-3.445c0-.701.196-1.351.514-1.924L21 17.932L24.584 16L30 24.755V6h4v22.555A3.98 3.98 0 0 1 36 32c0 .637-.162 1.23-.427 1.764L37 36.07l-3 1.615z");
}

</style>
